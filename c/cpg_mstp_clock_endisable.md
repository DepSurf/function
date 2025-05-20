# Function: <code>cpg_mstp_clock_endisable</code>

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
int cpg_mstp_clock_endisable(struct clk_hw *hw, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000107ec1d8)
Location: drivers/clk/renesas/renesas-cpg-mssr.c:164
Inline: False
Direct callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_disable
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_enable
```
**Symbols:**

```
ffff8000107ec1d8-ffff8000107ec448: cpg_mstp_clock_endisable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int cpg_mstp_clock_endisable(struct clk_hw *hw, bool enable);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/renesas-cpg-mssr.c (c09050fc)
Location: drivers/clk/renesas/renesas-cpg-mssr.c:164
Inline: False
Direct callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_disable
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mstp_clock_enable
```
```
In drivers/clk/renesas/clk-mstp.c (c09059f8)
Location: drivers/clk/renesas/clk-mstp.c:75
Inline: False
Direct callers:
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_disable
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clock_enable
```
**Symbols:**

```
c09050fc-c0905314: cpg_mstp_clock_endisable (STB_LOCAL)
c09059f8-c0905ba8: cpg_mstp_clock_endisable (STB_LOCAL)
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
