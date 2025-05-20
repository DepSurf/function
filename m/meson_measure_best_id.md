# Function: <code>meson_measure_best_id</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int meson_measure_best_id(struct meson_msr_id *clk_msr_id, unsigned int *precision);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/amlogic/meson-clk-measure.c (ffff800010819828)
Location: drivers/soc/amlogic/meson-clk-measure.c:538
Inline: False
Direct callers:
  - drivers/soc/amlogic/meson-clk-measure.c:clk_msr_summary_show
  - drivers/soc/amlogic/meson-clk-measure.c:clk_msr_show
```
**Symbols:**

```
ffff800010819828-ffff800010819a84: meson_measure_best_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int meson_measure_best_id(struct meson_msr_id *clk_msr_id, unsigned int *precision);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/amlogic/meson-clk-measure.c (c093654c)
Location: drivers/soc/amlogic/meson-clk-measure.c:538
Inline: False
Direct callers:
  - drivers/soc/amlogic/meson-clk-measure.c:clk_msr_summary_show
  - drivers/soc/amlogic/meson-clk-measure.c:clk_msr_show
```
**Symbols:**

```
c093654c-c09365c0: meson_measure_best_id (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
