# Function: <code>__clk_hw_register_composite</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, const struct clk_parent_data *pdata, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81704d90)
Location: drivers/clk/clk-composite.c:202
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81704d90-ffffffff8170509d: __clk_hw_register_composite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, const struct clk_parent_data *pdata, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81721fd0)
Location: drivers/clk/clk-composite.c:203
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81721fd0-ffffffff817222dd: __clk_hw_register_composite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, const struct clk_parent_data *pdata, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff817033e0)
Location: drivers/clk/clk-composite.c:203
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff817033e0-ffffffff817036eb: __clk_hw_register_composite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, const struct clk_parent_data *pdata, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff8177e0e0)
Location: drivers/clk/clk-composite.c:203
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff8177e0e0-ffffffff8177e3eb: __clk_hw_register_composite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, const struct clk_parent_data *pdata, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff818b4b40)
Location: drivers/clk/clk-composite.c:232
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff818b4b40-ffffffff818b4e82: __clk_hw_register_composite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, const struct clk_parent_data *pdata, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a017f0)
Location: drivers/clk/clk-composite.c:234
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81a017f0-ffffffff81a01b32: __clk_hw_register_composite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, const struct clk_parent_data *pdata, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a4a500)
Location: drivers/clk/clk-composite.c:237
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81a4a500-ffffffff81a4a842: __clk_hw_register_composite (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, const struct clk_parent_data *pdata, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a96050)
Location: drivers/clk/clk-composite.c:237
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81a96050-ffffffff81a963c1: __clk_hw_register_composite (STB_LOCAL)
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
