# Function: <code>clk_hw_register_fixed_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff8174e290)
Location: drivers/clk/clk-fixed-rate.c:117
Inline: False
```
**Symbols:**

```
ffffffff8174e290-ffffffff8174e2a3: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81536b00)
Location: drivers/clk/clk-fixed-rate.c:118
Inline: False
```
**Symbols:**

```
ffffffff81536b00-ffffffff81536b13: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81549e40)
Location: drivers/clk/clk-fixed-rate.c:118
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81549e40-ffffffff81549e53: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff815ad3c0)
Location: drivers/clk/clk-fixed-rate.c:118
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff815ad3c0-ffffffff815ad3d3: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff815e5550)
Location: drivers/clk/clk-fixed-rate.c:118
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff815e5550-ffffffff815e5563: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff815ff8e0)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff815ff8e0-ffffffff815ff8f3: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff816320a0)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff816320a0-ffffffff816320b3: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81653dd0)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff81653dd0-ffffffff81653de3: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
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
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffff8000107c50c8)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
```
**Symbols:**

```
ffff8000107c50c8-ffff8000107c5128: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (c08f0898)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_clk_probe
  - drivers/clk/clk-aspeed.c:aspeed_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/samsung/clk.c:samsung_clk_register_fixed_rate
```
**Symbols:**

```
c08f0898-c08f08c8: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffe0005125c0)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
```
**Symbols:**

```
ffffffe0005125c0-ffffffe00051260c: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81619e30)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81619e30-ffffffff81619e43: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff8160e360)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff8160e360-ffffffff8160e373: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81647c10)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff81647c10-ffffffff81647c23: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_rate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff816621a0)
Location: drivers/clk/clk-fixed-rate.c:115
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff816621a0-ffffffff816621b3: clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
