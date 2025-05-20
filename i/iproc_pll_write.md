# Function: <code>iproc_pll_write</code>

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
void iproc_pll_write(const struct iproc_pll *pll, void *base, const u32 offset, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/bcm/clk-iproc-pll.c (ffff8000107cb938)
Location: drivers/clk/bcm/clk-iproc-pll.c:173
Inline: False
Direct callers:
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_disable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_enable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_clk_enable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_disable
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:pll_set_rate
  - drivers/clk/bcm/clk-iproc-pll.c:__pll_enable
  - drivers/clk/bcm/clk-iproc-pll.c:__pll_enable
  - drivers/clk/bcm/clk-iproc-pll.c:__pll_enable
```
**Symbols:**

```
ffff8000107cb938-ffff8000107cb9b8: iproc_pll_write (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
