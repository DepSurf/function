# Function: <code>__clk_hw_register_gate</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:126
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff81704045-ffffffff8170405d: __clk_hw_register_gate.cold (STB_LOCAL)
ffffffff81703d10-ffffffff81703eab: __clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:126
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81c042ec-ffffffff81c04304: __clk_hw_register_gate.cold (STB_LOCAL)
ffffffff81720f60-ffffffff817210fb: __clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:126
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81bf5d47-ffffffff81bf5d5f: __clk_hw_register_gate.cold (STB_LOCAL)
ffffffff817022a0-ffffffff8170242e: __clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:126
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81cf3789-ffffffff81cf37a1: __clk_hw_register_gate.cold (STB_LOCAL)
ffffffff8177ce30-ffffffff8177cfbe: __clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-gate.c (0)
Location: drivers/clk/clk-gate.c:127
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:__devm_clk_hw_register_gate
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81ebba03-ffffffff81ebba1b: __clk_hw_register_gate.cold (STB_LOCAL)
ffffffff818b38d0-ffffffff818b3a72: __clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff81a00350)
Location: drivers/clk/clk-gate.c:127
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:__devm_clk_hw_register_gate
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81a00350-ffffffff81a0050d: __clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff81a49020)
Location: drivers/clk/clk-gate.c:127
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:__devm_clk_hw_register_gate
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81a49020-ffffffff81a491dd: __clk_hw_register_gate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_gate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 bit_idx, u8 clk_gate_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gate.c (ffffffff81a94b10)
Location: drivers/clk/clk-gate.c:127
Inline: False
Direct callers:
  - drivers/clk/clk-gate.c:__devm_clk_hw_register_gate
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81a94b10-ffffffff81a94cfc: __clk_hw_register_gate (STB_GLOBAL)
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
