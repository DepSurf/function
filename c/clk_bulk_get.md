# Function: <code>clk_bulk_get</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81543a30)
Location: drivers/clk/clk-bulk.c:32
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
```
**Symbols:**

```
ffffffff81543a30-ffffffff81543b22: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815a6b40)
Location: drivers/clk/clk-bulk.c:32
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
```
**Symbols:**

```
ffffffff815a6b40-ffffffff815a6c32: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815de850)
Location: drivers/clk/clk-bulk.c:32
Inline: True
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
```
**Symbols:**

```
ffffffff815de850-ffffffff815de949: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff815f8110)
Location: drivers/clk/clk-bulk.c:78
Inline: True
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
```
**Symbols:**

```
ffffffff815f8110-ffffffff815f8209: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8162a0d0)
Location: drivers/clk/clk-bulk.c:111
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff8162a0d0-ffffffff8162a0e2: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8164bb90)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff8164bb90-ffffffff8164bba2: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816fae60)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff816fae60-ffffffff816fae72: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81717810)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff81717810-ffffffff81717822: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff816f8b00)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff816f8b00-ffffffff816f8b12: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff817732c0)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff817732c0-ffffffff817732d2: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff818a8b70)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff818a8b70-ffffffff818a8b8e: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff819f3700)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff819f3700-ffffffff819f371e: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a3bdb0)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff81a3bdb0-ffffffff81a3bdce: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81a87670)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff81a87670-ffffffff81a8768e: clk_bulk_get (STB_GLOBAL)
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
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffff8000107ba5a0)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
```
**Symbols:**

```
ffff8000107ba5a0-ffff8000107ba5e8: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (c08e675c)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
```
**Symbols:**

```
c08e675c-c08e677c: clk_bulk_get (STB_GLOBAL)
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
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffe0005096d4)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_bulk_get
```
**Symbols:**

```
ffffffe0005096d4-ffffffe000509710: clk_bulk_get (STB_GLOBAL)
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
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81611bf0)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff81611bf0-ffffffff81611c02: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81606140)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff81606140-ffffffff81606152: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff8163f9d0)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff8163f9d0-ffffffff8163f9e2: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clk_bulk_get(struct device *dev, int num_clks, struct clk_bulk_data *clks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-bulk.c (ffffffff81659d20)
Location: drivers/clk/clk-bulk.c:114
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:__devm_clk_bulk_get
```
**Symbols:**

```
ffffffff81659d20-ffffffff81659d32: clk_bulk_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
