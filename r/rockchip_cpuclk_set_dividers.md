# Function: <code>rockchip_cpuclk_set_dividers</code>

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
In drivers/clk/rockchip/clk-cpu.c (ffff8000107ee548)
Location: drivers/clk/rockchip/clk-cpu.c:102
Inline: True
Direct callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
```
**Symbols:**

```
ffff8000107ee548-ffff8000107ee5e4: rockchip_cpuclk_set_dividers.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rockchip_cpuclk_set_dividers(struct rockchip_cpuclk *cpuclk, const struct rockchip_cpuclk_rate_table *rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/rockchip/clk-cpu.c (c0907df4)
Location: drivers/clk/rockchip/clk-cpu.c:102
Inline: False
Direct callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
```
**Symbols:**

```
c0907df4-c0907e90: rockchip_cpuclk_set_dividers (STB_LOCAL)
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
