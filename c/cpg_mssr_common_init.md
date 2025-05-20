# Function: <code>cpg_mssr_common_init</code>

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
int cpg_mssr_common_init(struct device *dev, struct device_node *np, const struct cpg_mssr_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff8000114888b8)
Location: drivers/clk/renesas/renesas-cpg-mssr.c:879
Inline: False
Direct callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_early_init
```
**Symbols:**

```
ffff8000114888b8-ffff8000114889e0: cpg_mssr_common_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpg_mssr_common_init(struct device *dev, struct device_node *np, const struct cpg_mssr_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/renesas-cpg-mssr.c (c1581728)
Location: drivers/clk/renesas/renesas-cpg-mssr.c:879
Inline: False
Direct callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_early_init
```
**Symbols:**

```
c1581728-c1581858: cpg_mssr_common_init (STB_LOCAL)
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
