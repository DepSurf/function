# Function: <code>__clk_pllv2_recalc_rate</code>

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
long unsigned int __clk_pllv2_recalc_rate(long unsigned int parent_rate, u32 dp_ctl, u32 dp_op, u32 dp_mfd, u32 dp_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-pllv2.c (ffff8000107d4d28)
Location: drivers/clk/imx/clk-pllv2.c:78
Inline: False
Direct callers:
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_round_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
```
**Symbols:**

```
ffff8000107d4d28-ffff8000107d4dc4: __clk_pllv2_recalc_rate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __clk_pllv2_recalc_rate(long unsigned int parent_rate, u32 dp_ctl, u32 dp_op, u32 dp_mfd, u32 dp_mfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-pllv2.c (c08fc03c)
Location: drivers/clk/imx/clk-pllv2.c:78
Inline: False
Direct callers:
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_round_rate
  - drivers/clk/imx/clk-pllv2.c:clk_pllv2_recalc_rate
```
**Symbols:**

```
c08fc03c-c08fc0f8: __clk_pllv2_recalc_rate (STB_LOCAL)
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
