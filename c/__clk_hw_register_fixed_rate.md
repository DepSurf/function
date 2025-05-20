# Function: <code>__clk_hw_register_fixed_rate</code>

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
struct clk_hw *__clk_hw_register_fixed_rate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81703b00)
Location: drivers/clk/clk-fixed-rate.c:52
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-st.c:st_clk_probe
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff81703b00-ffffffff81703c60: __clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_fixed_rate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81720d50)
Location: drivers/clk/clk-fixed-rate.c:52
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff81720d50-ffffffff81720eb0: __clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_fixed_rate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff817020a0)
Location: drivers/clk/clk-fixed-rate.c:52
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff817020a0-ffffffff817021ed: __clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_fixed_rate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff8177cc30)
Location: drivers/clk/clk-fixed-rate.c:52
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff8177cc30-ffffffff8177cd7d: __clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_fixed_rate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff818b3680)
Location: drivers/clk/clk-fixed-rate.c:52
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
```
**Symbols:**

```
ffffffff818b3680-ffffffff818b37d6: __clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_fixed_rate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags, bool devm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81a00040)
Location: drivers/clk/clk-fixed-rate.c:64
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
**Symbols:**

```
ffffffff81a00040-ffffffff81a00207: __clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_fixed_rate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags, bool devm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81a48d10)
Location: drivers/clk/clk-fixed-rate.c:64
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
**Symbols:**

```
ffffffff81a48d10-ffffffff81a48ed7: __clk_hw_register_fixed_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_hw *__clk_hw_register_fixed_rate(struct device *dev, struct device_node *np, const char *name, const char *parent_name, const struct clk_hw *parent_hw, const struct clk_parent_data *parent_data, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy, long unsigned int clk_fixed_flags, bool devm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81a947d0)
Location: drivers/clk/clk-fixed-rate.c:64
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-fch.c:fch_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
**Symbols:**

```
ffffffff81a947d0-ffffffff81a949ca: __clk_hw_register_fixed_rate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool devm</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
