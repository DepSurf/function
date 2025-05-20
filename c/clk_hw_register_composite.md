# Function: <code>clk_hw_register_composite</code>

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
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff8174f110)
Location: drivers/clk/clk-composite.c:214
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff8174f110-ffffffff8174f3db: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81537980)
Location: drivers/clk/clk-composite.c:214
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81537980-ffffffff81537c4b: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff8154ac60)
Location: drivers/clk/clk-composite.c:214
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff8154ac60-ffffffff8154af17: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff815ae280)
Location: drivers/clk/clk-composite.c:214
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff815ae280-ffffffff815ae531: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff815e64e0)
Location: drivers/clk/clk-composite.c:214
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff815e64e0-ffffffff815e6793: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff816008e0)
Location: drivers/clk/clk-composite.c:203
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff816008e0-ffffffff81600baa: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81633190)
Location: drivers/clk/clk-composite.c:203
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81633190-ffffffff8163344d: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81654ec0)
Location: drivers/clk/clk-composite.c:202
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81654ec0-ffffffff8165517d: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81705105)
Location: drivers/clk/clk-composite.c:319
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff817050a0-ffffffff817050c9: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81722349)
Location: drivers/clk/clk-composite.c:320
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff817222e0-ffffffff81722309: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81703759)
Location: drivers/clk/clk-composite.c:320
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff817036f0-ffffffff81703719: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff8177e459)
Location: drivers/clk/clk-composite.c:320
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff8177e3f0-ffffffff8177e419: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff818b4ed9)
Location: drivers/clk/clk-composite.c:349
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff818b4e90-ffffffff818b4ecb: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a01ba9)
Location: drivers/clk/clk-composite.c:351
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81a01b50-ffffffff81a01b8b: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a4a8b9)
Location: drivers/clk/clk-composite.c:354
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81a4a860-ffffffff81a4a89b: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a96439)
Location: drivers/clk/clk-composite.c:354
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81a963e0-ffffffff81a9641b: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffff8000107c69d0)
Location: drivers/clk/clk-composite.c:202
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_register
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_flags
  - drivers/clk/imx/clk-composite-7ulp.c:imx7ulp_clk_composite
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
```
**Symbols:**

```
ffff8000107c69d0-ffff8000107c6c60: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (c08f1b80)
Location: drivers/clk/clk-composite.c:202
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
  - drivers/clk/berlin/berlin2-div.c:berlin2_div_register
  - drivers/clk/imx/clk-composite-8m.c:imx8m_clk_composite_flags
  - drivers/clk/imx/clk-composite-7ulp.c:imx7ulp_clk_composite
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_init
```
**Symbols:**

```
c08f1b80-c08f1e54: clk_hw_register_composite (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffe000513a84)
Location: drivers/clk/clk-composite.c:202
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffe000513a84-ffffffe000513c70: clk_hw_register_composite (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff8161af20)
Location: drivers/clk/clk-composite.c:202
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff8161af20-ffffffff8161b1dd: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff8160f450)
Location: drivers/clk/clk-composite.c:202
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff8160f450-ffffffff8160f70d: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81648d00)
Location: drivers/clk/clk-composite.c:202
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81648d00-ffffffff81648fbd: clk_hw_register_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_composite(struct device *dev, const char *name, const const char * *parent_names, int num_parents, struct clk_hw *mux_hw, const struct clk_ops *mux_ops, struct clk_hw *rate_hw, const struct clk_ops *rate_ops, struct clk_hw *gate_hw, const struct clk_ops *gate_ops, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81663290)
Location: drivers/clk/clk-composite.c:202
Inline: False
Direct callers:
  - drivers/clk/clk-composite.c:clk_register_composite
```
**Symbols:**

```
ffffffff81663290-ffffffff8166354d: clk_hw_register_composite (STB_GLOBAL)
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
