# Function: <code>cpg_div6_register</code>

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
struct clk *cpg_div6_register(const char *name, unsigned int num_parents, const char **parent_names, void *reg, struct raw_notifier_head *notifiers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/clk-div6.c (ffff800011488e0c)
Location: drivers/clk/renesas/clk-div6.c:212
Inline: False
Direct callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init
```
**Symbols:**

```
ffff800011488e0c-ffff800011488fc4: cpg_div6_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *cpg_div6_register(const char *name, unsigned int num_parents, const char **parent_names, void *reg, struct raw_notifier_head *notifiers);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/renesas/clk-div6.c (c1582028)
Location: drivers/clk/renesas/clk-div6.c:212
Inline: False
Direct callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init
```
**Symbols:**

```
c1582028-c15821cc: cpg_div6_register (STB_GLOBAL)
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
