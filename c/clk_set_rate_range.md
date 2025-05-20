# Function: <code>clk_set_rate_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e7e90)
Location: drivers/clk/clk.c:1580
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_set_min_rate
  - drivers/clk/clk.c:clk_set_max_rate
```
**Symbols:**

```
ffffffff816e7e90-ffffffff816e7f2b: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174c430)
Location: drivers/clk/clk.c:1646
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_set_max_rate
  - drivers/clk/clk.c:clk_set_min_rate
```
**Symbols:**

```
ffffffff8174c430-ffffffff8174c4dc: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81534c90)
Location: drivers/clk/clk.c:1646
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_set_max_rate
  - drivers/clk/clk.c:clk_set_min_rate
```
**Symbols:**

```
ffffffff81534c90-ffffffff81534d3c: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81547ee0)
Location: drivers/clk/clk.c:1648
Inline: True
```
**Symbols:**

```
ffffffff81547ee0-ffffffff81547f71: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815aa250)
Location: drivers/clk/clk.c:1759
Inline: True
```
**Symbols:**

```
ffffffff815aa250-ffffffff815aa2e1: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2022
Inline: False
```
**Symbols:**

```
ffffffff815e4413-ffffffff815e4444: clk_set_rate_range.cold.57 (STB_LOCAL)
ffffffff815e29c0-ffffffff815e2ad1: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2135
Inline: False
```
**Symbols:**

```
ffffffff815fe85c-ffffffff815fe88d: clk_set_rate_range.cold.62 (STB_LOCAL)
ffffffff815fd050-ffffffff815fd161: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2271
Inline: False
```
**Symbols:**

```
ffffffff81630fd1-ffffffff81631002: clk_set_rate_range.cold (STB_LOCAL)
ffffffff816304d0-ffffffff816305da: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2279
Inline: False
```
**Symbols:**

```
ffffffff81652cad-ffffffff81652cde: clk_set_rate_range.cold (STB_LOCAL)
ffffffff81651880-ffffffff8165198a: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2300
Inline: False
```
**Symbols:**

```
ffffffff817029e8-ffffffff81702a19: clk_set_rate_range.cold (STB_LOCAL)
ffffffff817022c0-ffffffff81702494: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171f810)
Location: drivers/clk/clk.c:2309
Inline: True
```
**Symbols:**

```
ffffffff8171f600-ffffffff8171f802: clk_set_rate_range.part.0 (STB_LOCAL)
ffffffff81c042a2-ffffffff81c042d4: clk_set_rate_range.part.0.cold (STB_LOCAL)
ffffffff8171f810-ffffffff8171f828: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81700830)
Location: drivers/clk/clk.c:2322
Inline: True
```
**Symbols:**

```
ffffffff81700620-ffffffff81700822: clk_set_rate_range.part.0 (STB_LOCAL)
ffffffff81bf5cfd-ffffffff81bf5d2f: clk_set_rate_range.part.0.cold (STB_LOCAL)
ffffffff81700830-ffffffff81700848: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8177b040)
Location: drivers/clk/clk.c:2322
Inline: True
```
**Symbols:**

```
ffffffff8177ae30-ffffffff8177b032: clk_set_rate_range.part.0 (STB_LOCAL)
ffffffff81cf338f-ffffffff81cf33c1: clk_set_rate_range.part.0.cold (STB_LOCAL)
ffffffff8177b040-ffffffff8177b058: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b17d0)
Location: drivers/clk/clk.c:2336
Inline: True
```
**Symbols:**

```
ffffffff818b1580-ffffffff818b17c5: clk_set_rate_range.part.0 (STB_LOCAL)
ffffffff81ebb5fa-ffffffff81ebb62d: clk_set_rate_range.part.0.cold (STB_LOCAL)
ffffffff818b17d0-ffffffff818b17fc: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fd4d0)
Location: drivers/clk/clk.c:2591
Inline: True
```
**Symbols:**

```
ffffffff819fd4d0-ffffffff819fd522: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a46990)
Location: drivers/clk/clk.c:2636
Inline: True
```
**Symbols:**

```
ffffffff81a46990-ffffffff81a469e2: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a92480)
Location: drivers/clk/clk.c:2636
Inline: True
```
**Symbols:**

```
ffffffff81a92480-ffffffff81a924d2: clk_set_rate_range (STB_GLOBAL)
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
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c2440)
Location: drivers/clk/clk.c:2279
Inline: False
```
**Symbols:**

```
ffff8000107c2440-ffff8000107c2584: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ed03c)
Location: drivers/clk/clk.c:2279
Inline: False
```
**Symbols:**

```
c08ed03c-c08ed190: clk_set_rate_range (STB_GLOBAL)
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
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050ff96)
Location: drivers/clk/clk.c:2279
Inline: False
```
**Symbols:**

```
ffffffe00050ff96-ffffffe0005100a4: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2279
Inline: False
```
**Symbols:**

```
ffffffff81618d0d-ffffffff81618d3e: clk_set_rate_range.cold (STB_LOCAL)
ffffffff816178e0-ffffffff816179ea: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2279
Inline: False
```
**Symbols:**

```
ffffffff8160d23d-ffffffff8160d26e: clk_set_rate_range.cold (STB_LOCAL)
ffffffff8160be10-ffffffff8160bf1a: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2279
Inline: False
```
**Symbols:**

```
ffffffff81646aed-ffffffff81646b1e: clk_set_rate_range.cold (STB_LOCAL)
ffffffff816456c0-ffffffff816457ca: clk_set_rate_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int clk_set_rate_range(struct clk *clk, long unsigned int min, long unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2279
Inline: False
```
**Symbols:**

```
ffffffff8166107d-ffffffff816610ae: clk_set_rate_range.cold (STB_LOCAL)
ffffffff8165fc50-ffffffff8165fd5a: clk_set_rate_range (STB_GLOBAL)
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
