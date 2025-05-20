# Function: <code>__clk_hw_register_divider</code>

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
struct clk_hw *__clk_hw_register_divider(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_register_divider_table
```
**Symbols:**

```
ffffffff817037a7-ffffffff817037bf: __clk_hw_register_divider.cold (STB_LOCAL)
ffffffff81702cf0-ffffffff81702e53: __clk_hw_register_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_divider(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:467
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider_table
```
**Symbols:**

```
ffffffff81c042d4-ffffffff81c042ec: __clk_hw_register_divider.cold (STB_LOCAL)
ffffffff8171fe40-ffffffff8171ffe8: __clk_hw_register_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_divider(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:467
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider_table
```
**Symbols:**

```
ffffffff81bf5d2f-ffffffff81bf5d47: __clk_hw_register_divider.cold (STB_LOCAL)
ffffffff81701090-ffffffff8170122b: __clk_hw_register_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_divider(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:537
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider_table
```
**Symbols:**

```
ffffffff81cf34f9-ffffffff81cf3511: __clk_hw_register_divider.cold (STB_LOCAL)
ffffffff8177b9d0-ffffffff8177bb6b: __clk_hw_register_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct clk_hw *__clk_hw_register_divider(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:537
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider_table
```
**Symbols:**

```
ffffffff81ebb761-ffffffff81ebb779: __clk_hw_register_divider.cold (STB_LOCAL)
ffffffff818b22e0-ffffffff818b2489: __clk_hw_register_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_divider(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff819fe9c0)
Location: drivers/clk/clk-divider.c:537
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider_table
```
**Symbols:**

```
ffffffff819fe9c0-ffffffff819feb87: __clk_hw_register_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_divider(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81a47680)
Location: drivers/clk/clk-divider.c:537
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider_table
```
**Symbols:**

```
ffffffff81a47680-ffffffff81a47847: __clk_hw_register_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_divider(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81a93120)
Location: drivers/clk/clk-divider.c:537
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:__devm_clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider_table
```
**Symbols:**

```
ffffffff81a93120-ffffffff81a93316: __clk_hw_register_divider (STB_GLOBAL)
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
