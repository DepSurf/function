# Function: <code>clk_register_fixed_rate_with_accuracy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff816e9ae0)
Location: drivers/clk/clk-fixed-rate.c:59
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff816e9ae0-ffffffff816e9bca: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff8174e2d6)
Location: drivers/clk/clk-fixed-rate.c:94
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff8174e2b0-ffffffff8174e2cc: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81536b46)
Location: drivers/clk/clk-fixed-rate.c:95
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff81536b20-ffffffff81536b3c: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81549e86)
Location: drivers/clk/clk-fixed-rate.c:95
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff81549e60-ffffffff81549e7c: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff815ad406)
Location: drivers/clk/clk-fixed-rate.c:95
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff815ad3e0-ffffffff815ad3fc: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff815e5595)
Location: drivers/clk/clk-fixed-rate.c:95
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff815e5570-ffffffff815e558c: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff815ff925)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff815ff900-ffffffff815ff91c: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff816320e5)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff816320c0-ffffffff816320dc: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81653e15)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff81653df0-ffffffff81653e0c: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffff8000107c5314)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffff8000107c5128-ffff8000107c5198: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (c08f0a30)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
c08f08c8-c08f0904: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
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
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffe0005127a6)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffe00051260c-ffffffe000512666: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
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
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81619e75)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff81619e50-ffffffff81619e6c: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff8160e3a5)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff8160e380-ffffffff8160e39c: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff81647c55)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff81647c30-ffffffff81647c4c: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_fixed_rate_with_accuracy(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, long unsigned int fixed_rate, long unsigned int fixed_accuracy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fixed-rate.c (ffffffff816621e5)
Location: drivers/clk/clk-fixed-rate.c:92
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate
```
**Symbols:**

```
ffffffff816621c0-ffffffff816621dc: clk_register_fixed_rate_with_accuracy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
