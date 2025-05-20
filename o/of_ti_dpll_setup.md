# Function: <code>of_ti_dpll_setup</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void of_ti_dpll_setup(struct device_node *node, const struct clk_ops *ops, const struct dpll_data *ddt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/ti/dpll.c (c158a2d0)
Location: drivers/clk/ti/dpll.c:285
Inline: False
Direct callers:
  - drivers/clk/ti/dpll.c:of_ti_omap2_core_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_am3_core_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_am3_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_am3_no_gate_jtype_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_am3_jtype_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_am3_no_gate_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap4_jtype_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap4_m4xen_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap4_core_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap5_mpu_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap4_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap3_per_jtype_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap3_per_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap3_core_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap3_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap3_dpll_setup
```
**Symbols:**

```
c158a2d0-c158a504: of_ti_dpll_setup (STB_LOCAL)
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
