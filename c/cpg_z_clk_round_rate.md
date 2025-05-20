# Function: <code>cpg_z_clk_round_rate</code>

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
long int cpg_z_clk_round_rate(struct clk_hw *hw, long unsigned int rate, long unsigned int *parent_rate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/rcar-gen3-cpg.c (ffff8000107eadd0)
Location: drivers/clk/renesas/rcar-gen3-cpg.c:117
Inline: False
```
**Symbols:**

```
ffff8000107eadd0-ffff8000107eae38: cpg_z_clk_round_rate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
long int cpg_z_clk_round_rate(struct clk_hw *hw, long unsigned int rate, long unsigned int *parent_rate);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/clk-rcar-gen2.c (c0904768)
Location: drivers/clk/renesas/clk-rcar-gen2.c:69
Inline: False
```
```
In drivers/clk/renesas/rcar-gen2-cpg.c (c0904998)
Location: drivers/clk/renesas/rcar-gen2-cpg.c:66
Inline: False
```
**Symbols:**

```
c0904768-c09047d8: cpg_z_clk_round_rate (STB_LOCAL)
c0904998-c0904a08: cpg_z_clk_round_rate (STB_LOCAL)
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
