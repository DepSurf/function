# Function: <code>__clk_create_clk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct clk *__clk_create_clk(struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e8340)
Location: drivers/clk/clk.c:2479
Inline: False
Direct callers:
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff816e8340-ffffffff816e83f5: __clk_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *__clk_create_clk(struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174cb1d)
Location: drivers/clk/clk.c:2487
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
Direct callers:
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff8174b970-ffffffff8174ba08: __clk_create_clk.part.30 (STB_LOCAL)
ffffffff8174c900-ffffffff8174c925: __clk_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *__clk_create_clk(struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8153537d)
Location: drivers/clk/clk.c:2490
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
Direct callers:
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff815341e0-ffffffff81534278: __clk_create_clk.part.32 (STB_LOCAL)
ffffffff81535160-ffffffff81535185: __clk_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *__clk_create_clk(struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81548794)
Location: drivers/clk/clk.c:2523
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
Direct callers:
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff81546b50-ffffffff81546bf5: __clk_create_clk.part.42 (STB_LOCAL)
ffffffff81548560-ffffffff81548585: __clk_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *__clk_create_clk(struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff815abc36)
Location: drivers/clk/clk.c:2654
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
Direct callers:
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff815aa560-ffffffff815aa605: __clk_create_clk.part.44 (STB_LOCAL)
ffffffff815ab9e0-ffffffff815aba05: __clk_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *__clk_create_clk(struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e3c2a)
Location: drivers/clk/clk.c:2911
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
Direct callers:
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff815e1810-ffffffff815e18b5: __clk_create_clk.part.52 (STB_LOCAL)
ffffffff815e39c0-ffffffff815e39e5: __clk_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct clk *__clk_create_clk(struct clk_hw *hw, const char *dev_id, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fe00a)
Location: drivers/clk/clk.c:3212
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
Direct callers:
  - drivers/clk/clkdev.c:clk_get_sys
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff815fb980-ffffffff815fba25: __clk_create_clk.part.57 (STB_LOCAL)
ffffffff815fdda0-ffffffff815fddc5: __clk_create_clk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
</ul>
