# Function: <code>__devm_clk_hw_register_gate</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk_hw *__devm_clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff818b3ae0)
Location: drivers/clk/clk-gate.c:232
Inline: False
```
**Symbols:**

```
ffffffff818b3ae0-ffffffff818b3bc3: __devm_clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_hw *__devm_clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff81a00590)
Location: drivers/clk/clk-gate.c:232
Inline: False
```
**Symbols:**

```
ffffffff81a00590-ffffffff81a00673: __devm_clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_hw *__devm_clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff81a49260)
Location: drivers/clk/clk-gate.c:232
Inline: False
```
**Symbols:**

```
ffffffff81a49260-ffffffff81a49343: __devm_clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_hw *__devm_clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff81a94d80)
Location: drivers/clk/clk-gate.c:232
Inline: False
```
**Symbols:**

```
ffffffff81a94d80-ffffffff81a94e63: __devm_clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
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
