# Function: <code>clk_hw_register_gate</code>

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
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff8174e470)
Location: drivers/clk/clk-gate.c:123
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
```
**Symbols:**

```
ffffffff8174e470-ffffffff8174e593: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff81536ce0)
Location: drivers/clk/clk-gate.c:123
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
```
**Symbols:**

```
ffffffff81536ce0-ffffffff81536e03: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff8154a030)
Location: drivers/clk/clk-gate.c:123
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
```
**Symbols:**

```
ffffffff8154a030-ffffffff8154a154: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff815ad5b0)
Location: drivers/clk/clk-gate.c:124
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
```
**Symbols:**

```
ffffffff815ad5b0-ffffffff815ad6d4: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff815e5740)
Location: drivers/clk/clk-gate.c:124
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff815e5740-ffffffff815e5862: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff815ffad0)
Location: drivers/clk/clk-gate.c:121
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff815ffad0-ffffffff815ffbf2: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:137
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff8163245f-ffffffff81632477: clk_hw_register_gate.cold (STB_LOCAL)
ffffffff816322c0-ffffffff816323ca: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:137
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff8165418f-ffffffff816541a7: clk_hw_register_gate.cold (STB_LOCAL)
ffffffff81653ff0-ffffffff816540fa: clk_hw_register_gate (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffff8000107c5420)
Location: drivers/clk/clk-gate.c:137
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_probe
  - drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_probe
  - drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
```
**Symbols:**

```
ffff8000107c5420-ffff8000107c5558: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (c08f0b20)
Location: drivers/clk/clk-gate.c:137
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/clk-aspeed.c:aspeed_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/berlin/bg2.c:berlin2_clock_setup
  - drivers/clk/berlin/bg2q.c:berlin2q_clock_setup
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
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
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
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init
  - drivers/clk/samsung/clk.c:samsung_clk_register_gate
```
**Symbols:**

```
c08f0b20-c08f0c58: clk_hw_register_gate (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffe00051288c)
Location: drivers/clk/clk-gate.c:137
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
```
**Symbols:**

```
ffffffe00051288c-ffffffe000512984: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:137
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
```
**Symbols:**

```
ffffffff8161a1ef-ffffffff8161a207: clk_hw_register_gate.cold (STB_LOCAL)
ffffffff8161a050-ffffffff8161a15a: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:137
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff8160e71f-ffffffff8160e737: clk_hw_register_gate.cold (STB_LOCAL)
ffffffff8160e580-ffffffff8160e68a: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:137
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff81647fcf-ffffffff81647fe7: clk_hw_register_gate.cold (STB_LOCAL)
ffffffff81647e30-ffffffff81647f3a: clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_gate(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:137
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff8166255f-ffffffff81662577: clk_hw_register_gate.cold (STB_LOCAL)
ffffffff816623c0-ffffffff816624ca: clk_hw_register_gate (STB_GLOBAL)
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
