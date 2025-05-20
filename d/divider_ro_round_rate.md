# Function: <code>divider_ro_round_rate</code>

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
In drivers/clk/clk-divider.c (ffffffff815e4f5a)
Location: include/linux/clk-provider.h:791
Inline: True
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
In drivers/clk/clk-divider.c (ffffffff815ff57a)
Location: include/linux/clk-provider.h:827
Inline: True
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
In drivers/clk/clk-divider.c (ffffffff81631b79)
Location: include/linux/clk-provider.h:859
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_round_rate
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
In drivers/clk/clk-divider.c (ffffffff816538a9)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_round_rate
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
In drivers/clk/clk-divider.c (ffffffff81703723)
Location: include/linux/clk-provider.h:1136
Inline: True
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
In drivers/clk/clk-divider.c (ffffffff81720983)
Location: include/linux/clk-provider.h:1174
Inline: True
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
In drivers/clk/clk-divider.c (ffffffff81701baf)
Location: include/linux/clk-provider.h:1206
Inline: True
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
In drivers/clk/clk-divider.c (ffffffff8177c667)
Location: include/linux/clk-provider.h:1218
Inline: True
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
In drivers/clk/clk-divider.c (ffffffff818b2fde)
Location: include/linux/clk-provider.h:1244
Inline: True
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
In drivers/clk/clk-divider.c (ffffffff819ff785)
Location: include/linux/clk-provider.h:1340
Inline: True
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
In drivers/clk/clk-divider.c (ffffffff81a48455)
Location: include/linux/clk-provider.h:1359
Inline: True
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
In drivers/clk/clk-divider.c (ffffffff81a93ef5)
Location: include/linux/clk-provider.h:1360
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffff8000107c4928)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_round_rate
```
```
In drivers/clk/meson/clk-regmap.c (ffff8000107e7ef8)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/meson/clk-regmap.c:clk_regmap_div_round_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (c08f01bc)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_round_rate
```
```
In drivers/clk/clk-milbeaut.c (c08f51ac)
Location: include/linux/clk-provider.h:861
Inline: True
```
```
In drivers/clk/meson/clk-regmap.c (c0902fb0)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/meson/clk-regmap.c:clk_regmap_div_round_rate
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffe000511f34)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_round_rate
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
In drivers/clk/clk-divider.c (ffffffff81619909)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_round_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff8160de39)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_round_rate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff816476e9)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_round_rate
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
In drivers/clk/clk-divider.c (ffffffff81661c79)
Location: include/linux/clk-provider.h:861
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_round_rate
```
</details>
</li>
</ul>

## Differences
