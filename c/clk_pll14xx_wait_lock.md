# Function: <code>clk_pll14xx_wait_lock</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/imx/clk-pll14xx.c (ffff8000107d6ac8)
Location: drivers/clk/imx/clk-pll14xx.c:126
Inline: True
Direct callers:
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
```
**Symbols:**

```
ffff8000107d6ac8-ffff8000107d6b48: clk_pll14xx_wait_lock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_pll14xx_wait_lock(struct clk_pll14xx *pll);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/imx/clk-pll14xx.c (c08fde54)
Location: drivers/clk/imx/clk-pll14xx.c:126
Inline: False
Direct callers:
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_prepare
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1443x_set_rate
  - drivers/clk/imx/clk-pll14xx.c:clk_pll1416x_set_rate
```
**Symbols:**

```
c08fde54-c08fdecc: clk_pll14xx_wait_lock (STB_LOCAL)
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
