# Function: <code>clk_hw_register_fixed_factor</code>

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
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff8174dfc0)
Location: drivers/clk/clk-fixed-factor.c:71
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff8174dfc0-ffffffff8174e096: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81536830)
Location: drivers/clk/clk-fixed-factor.c:72
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81536830-ffffffff81536906: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81549b70)
Location: drivers/clk/clk-fixed-factor.c:72
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81549b70-ffffffff81549c48: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff815ad0f0)
Location: drivers/clk/clk-fixed-factor.c:72
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff815ad0f0-ffffffff815ad1c8: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff815e5280)
Location: drivers/clk/clk-fixed-factor.c:72
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff815e5280-ffffffff815e5356: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff815ff670)
Location: drivers/clk/clk-fixed-factor.c:67
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff815ff670-ffffffff815ff746: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81631f75)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81631f90-ffffffff81631fa0: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81653ca5)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81653cc0-ffffffff81653cd0: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81703a35)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81703a50-ffffffff81703a60: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81720c85)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81720ca0-ffffffff81720cb0: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81701fa5)
Location: drivers/clk/clk-fixed-factor.c:134
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81701fe0-ffffffff81701ff2: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff8177cb35)
Location: drivers/clk/clk-fixed-factor.c:134
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff8177cb70-ffffffff8177cb82: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff818b34e5)
Location: drivers/clk/clk-fixed-factor.c:156
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff818b3560-ffffffff818b3591: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff819ffec5)
Location: drivers/clk/clk-fixed-factor.c:191
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff819ffd80-ffffffff819ffdb3: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81a48b95)
Location: drivers/clk/clk-fixed-factor.c:191
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81a48a50-ffffffff81a48a83: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81a94655)
Location: drivers/clk/clk-fixed-factor.c:191
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81a94510-ffffffff81a94543: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffff8000107c4c74)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
Direct callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_pll_divider
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/zynqmp/clkc.c:zynqmp_clk_register_fixed_factor
```
**Symbols:**

```
ffff8000107c4bd0-ffff8000107c4c3c: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (c08f04cc)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
Direct callers:
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-aspeed.c:aspeed_ast2500_calc_pll
  - drivers/clk/clk-aspeed.c:aspeed_ast2400_calc_pll
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:aspeed_g6_cc
  - drivers/clk/clk-ast2600.c:ast2600_calc_pll
  - drivers/clk/clk-milbeaut.c:m10v_reg_fixed_pre
  - drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init
  - drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init
  - drivers/clk/berlin/bg2.c:berlin2_clock_setup
  - drivers/clk/berlin/bg2q.c:berlin2q_clock_setup
  - drivers/clk/berlin/bg2q.c:berlin2q_clock_setup
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx5_clocks_common_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/samsung/clk.c:samsung_clk_register_fixed_factor
```
**Symbols:**

```
c08f0468-c08f04b4: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffe00051223c)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffe0005121bc-ffffffe000512212: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81619d05)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81619d20-ffffffff81619d30: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff8160e235)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff8160e250-ffffffff8160e260: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81647ae5)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81647b00-ffffffff81647b10: clk_hw_register_fixed_factor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fixed_factor(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, unsigned int mult, unsigned int div);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-factor.c (ffffffff81662075)
Location: drivers/clk/clk-fixed-factor.c:109
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
```
**Symbols:**

```
ffffffff81662090-ffffffff816620a0: clk_hw_register_fixed_factor (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
