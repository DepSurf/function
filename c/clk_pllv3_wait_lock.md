# Function: <code>clk_pllv3_wait_lock</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int clk_pllv3_wait_lock(struct clk_pllv3 *pll);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-pllv3.c (ffff8000107d5548)
Location: drivers/clk/imx/clk-pllv3.c:54
Inline: True
Direct callers:
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_prepare
```
**Symbols:**

```
ffff8000107d5548-ffff8000107d55e0: clk_pllv3_wait_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_pllv3_wait_lock(struct clk_pllv3 *pll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-pllv3.c (c08fc414)
Location: drivers/clk/imx/clk-pllv3.c:54
Inline: False
Direct callers:
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_vf610_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_av_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_sys_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_set_rate
  - drivers/clk/imx/clk-pllv3.c:clk_pllv3_prepare
```
**Symbols:**

```
c08fc414-c08fc4c8: clk_pllv3_wait_lock (STB_LOCAL)
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
