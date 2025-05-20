# Function: <code>clk_hw_register_clkdev</code>

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
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff817484c0)
Location: drivers/clk/clkdev.c:452
Inline: False
```
**Symbols:**

```
ffffffff817484c0-ffffffff817484fa: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81530d30)
Location: drivers/clk/clkdev.c:457
Inline: False
```
**Symbols:**

```
ffffffff81530d30-ffffffff81530d76: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81544220)
Location: drivers/clk/clkdev.c:457
Inline: False
```
**Symbols:**

```
ffffffff81544220-ffffffff81544266: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815a7330)
Location: drivers/clk/clkdev.c:457
Inline: False
```
**Symbols:**

```
ffffffff815a7330-ffffffff815a7376: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815deeb0)
Location: drivers/clk/clkdev.c:457
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff815deeb0-ffffffff815deef6: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff815f87e0)
Location: drivers/clk/clkdev.c:454
Inline: True
Direct callers:
  - drivers/clk/x86/clk-st.c:st_clk_probe
```
**Symbols:**

```
ffffffff815f87e0-ffffffff815f8826: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8162a7f0)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffffffff8162a7f0-ffffffff8162a831: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8164c2b0)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffffffff8164c2b0-ffffffff8164c2f1: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816fb5c0)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffffffff816fb5c0-ffffffff816fb606: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81717f10)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffffffff81717f10-ffffffff81717f56: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816f9200)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffffffff816f9200-ffffffff816f9246: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81773960)
Location: drivers/clk/clkdev.c:340
Inline: False
```
**Symbols:**

```
ffffffff81773960-ffffffff817739a6: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff818a92e0)
Location: drivers/clk/clkdev.c:340
Inline: False
```
**Symbols:**

```
ffffffff818a92e0-ffffffff818a934a: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff819f3bc0)
Location: drivers/clk/clkdev.c:340
Inline: False
```
**Symbols:**

```
ffffffff819f3bc0-ffffffff819f3c2a: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a3c180)
Location: drivers/clk/clkdev.c:340
Inline: False
```
**Symbols:**

```
ffffffff81a3c180-ffffffff81a3c1ea: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81a87a40)
Location: drivers/clk/clkdev.c:340
Inline: False
```
**Symbols:**

```
ffffffff81a87a40-ffffffff81a87aaa: clk_hw_register_clkdev (STB_GLOBAL)
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
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffff8000107baf98)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffff8000107baf98-ffff8000107bb004: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (c08e6ec8)
Location: drivers/clk/clkdev.c:368
Inline: False
Direct callers:
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/samsung/clk.c:samsung_clk_register_fixed_rate
  - drivers/clk/samsung/clk.c:samsung_clk_register_alias
```
**Symbols:**

```
c08e6ec8-c08e6f28: clk_hw_register_clkdev (STB_GLOBAL)
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
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffe000509ed0)
Location: drivers/clk/clkdev.c:368
Inline: False
Direct callers:
  - drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_probe
```
**Symbols:**

```
ffffffe000509ed0-ffffffe000509f0e: clk_hw_register_clkdev (STB_GLOBAL)
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
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81612310)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffffffff81612310-ffffffff81612351: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff81606860)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffffffff81606860-ffffffff816068a1: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff816400f0)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffffffff816400f0-ffffffff81640131: clk_hw_register_clkdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clk_hw_register_clkdev(struct clk_hw *hw, const char *con_id, const char *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clkdev.c (ffffffff8165a440)
Location: drivers/clk/clkdev.c:368
Inline: False
```
**Symbols:**

```
ffffffff8165a440-ffffffff8165a481: clk_hw_register_clkdev (STB_GLOBAL)
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
