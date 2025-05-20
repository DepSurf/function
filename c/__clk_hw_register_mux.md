# Function: <code>__clk_hw_register_mux</code>

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
struct clk_hw *__clk_hw_register_mux(struct device *dev, struct device_node *np, const char *name, u8 num_parents, const const char * *parent_names, const struct clk_hw **parent_hws, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_register_mux_table
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff8170483c-ffffffff81704854: __clk_hw_register_mux.cold (STB_LOCAL)
ffffffff817044d0-ffffffff81704691: __clk_hw_register_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_mux(struct device *dev, struct device_node *np, const char *name, u8 num_parents, const const char * *parent_names, const struct clk_hw **parent_hws, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_register_mux_table
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81c04304-ffffffff81c0431c: __clk_hw_register_mux.cold (STB_LOCAL)
ffffffff81721710-ffffffff817218d1: __clk_hw_register_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_mux(struct device *dev, struct device_node *np, const char *name, u8 num_parents, const const char * *parent_names, const struct clk_hw **parent_hws, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:149
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_register_mux_table
  - drivers/clk/clk-mux.c:__devm_clk_hw_register_mux
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81bf5d5f-ffffffff81bf5d77: __clk_hw_register_mux.cold (STB_LOCAL)
ffffffff81702a40-ffffffff81702c01: __clk_hw_register_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_mux(struct device *dev, struct device_node *np, const char *name, u8 num_parents, const const char * *parent_names, const struct clk_hw **parent_hws, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:149
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_register_mux_table
  - drivers/clk/clk-mux.c:__devm_clk_hw_register_mux
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81cf395f-ffffffff81cf3977: __clk_hw_register_mux.cold (STB_LOCAL)
ffffffff8177d6d0-ffffffff8177d891: __clk_hw_register_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_mux(struct device *dev, struct device_node *np, const char *name, u8 num_parents, const const char * *parent_names, const struct clk_hw **parent_hws, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:149
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_register_mux_table
  - drivers/clk/clk-mux.c:__devm_clk_hw_register_mux
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81ebbbe5-ffffffff81ebbbfd: __clk_hw_register_mux.cold (STB_LOCAL)
ffffffff818b4310-ffffffff818b44e6: __clk_hw_register_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_mux(struct device *dev, struct device_node *np, const char *name, u8 num_parents, const const char * *parent_names, const struct clk_hw **parent_hws, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81a00ea0)
Location: drivers/clk/clk-mux.c:149
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_register_mux_table
  - drivers/clk/clk-mux.c:__devm_clk_hw_register_mux
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81a00ea0-ffffffff81a0109a: __clk_hw_register_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_mux(struct device *dev, struct device_node *np, const char *name, u8 num_parents, const const char * *parent_names, const struct clk_hw **parent_hws, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81a49ba0)
Location: drivers/clk/clk-mux.c:149
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_register_mux_table
  - drivers/clk/clk-mux.c:__devm_clk_hw_register_mux
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81a49ba0-ffffffff81a49d9a: __clk_hw_register_mux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_mux(struct device *dev, struct device_node *np, const char *name, u8 num_parents, const const char * *parent_names, const struct clk_hw **parent_hws, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81a956c0)
Location: drivers/clk/clk-mux.c:149
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_register_mux_table
  - drivers/clk/clk-mux.c:__devm_clk_hw_register_mux
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81a956c0-ffffffff81a958e9: __clk_hw_register_mux (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 *table</code> ➡️ <code>const u32 *table</code>
</li>
</ul>
</details>
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
