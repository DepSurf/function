# Function: <code>clk_hw_register_composite_pdata</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite_pdata(struct device *dev, const char *name, const struct clk_parent_data *parent_data, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81705145)
Location: drivers/clk/clk-composite.c:332
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
```
**Symbols:**

```
ffffffff817050d0-ffffffff817050fc: clk_hw_register_composite_pdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite_pdata(struct device *dev, const char *name, const struct clk_parent_data *parent_data, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81722389)
Location: drivers/clk/clk-composite.c:334
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
```
**Symbols:**

```
ffffffff81722310-ffffffff8172233c: clk_hw_register_composite_pdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite_pdata(struct device *dev, const char *name, const struct clk_parent_data *parent_data, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81703799)
Location: drivers/clk/clk-composite.c:334
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
```
**Symbols:**

```
ffffffff81703720-ffffffff8170374c: clk_hw_register_composite_pdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite_pdata(struct device *dev, const char *name, const struct clk_parent_data *parent_data, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff8177e499)
Location: drivers/clk/clk-composite.c:334
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
```
**Symbols:**

```
ffffffff8177e420-ffffffff8177e44c: clk_hw_register_composite_pdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite_pdata(struct device *dev, const char *name, const struct clk_parent_data *parent_data, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff818b5289)
Location: drivers/clk/clk-composite.c:363
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
```
**Symbols:**

```
ffffffff818b5240-ffffffff818b527e: clk_hw_register_composite_pdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite_pdata(struct device *dev, const char *name, const struct clk_parent_data *parent_data, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a01fe9)
Location: drivers/clk/clk-composite.c:365
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
```
**Symbols:**

```
ffffffff81a01f90-ffffffff81a01fce: clk_hw_register_composite_pdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite_pdata(struct device *dev, const char *name, const struct clk_parent_data *parent_data, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a4ad09)
Location: drivers/clk/clk-composite.c:368
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
```
**Symbols:**

```
ffffffff81a4acb0-ffffffff81a4acee: clk_hw_register_composite_pdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite_pdata(struct device *dev, const char *name, const struct clk_parent_data *parent_data, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a96889)
Location: drivers/clk/clk-composite.c:368
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite_pdata
```
**Symbols:**

```
ffffffff81a96830-ffffffff81a9686e: clk_hw_register_composite_pdata (STB_GLOBAL)
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
