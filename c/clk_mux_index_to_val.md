# Function: <code>clk_mux_index_to_val</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff815e5ba7)
Location: drivers/clk/clk-mux.c:56
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff815e5b50-ffffffff815e5b90: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff815fff97)
Location: drivers/clk/clk-mux.c:53
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff815fff40-ffffffff815fff80: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff816328d2)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff81632790-ffffffff816327ce: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81654602)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff816544c0-ffffffff816544fe: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81704752)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff81704370-ffffffff817043ae: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81721999)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff817215b0-ffffffff817215ee: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81702da9)
Location: drivers/clk/clk-mux.c:70
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff817028b0-ffffffff817028ee: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8177da4f)
Location: drivers/clk/clk-mux.c:70
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff81cf3940-ffffffff81cf395f: clk_mux_index_to_val.cold (STB_LOCAL)
ffffffff8177d5b0-ffffffff8177d606: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(const u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff818b46cf)
Location: drivers/clk/clk-mux.c:70
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff81ebbbc6-ffffffff81ebbbe5: clk_mux_index_to_val.cold (STB_LOCAL)
ffffffff818b41d0-ffffffff818b424a: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(const u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81a012bf)
Location: drivers/clk/clk-mux.c:70
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff820934aa-ffffffff820934c9: clk_mux_index_to_val.cold (STB_LOCAL)
ffffffff81a00c50-ffffffff81a00cca: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(const u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81a49fbd)
Location: drivers/clk/clk-mux.c:70
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff821141b0-ffffffff821141cf: clk_mux_index_to_val.cold (STB_LOCAL)
ffffffff81a49950-ffffffff81a499ca: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(const u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81a95b0d)
Location: drivers/clk/clk-mux.c:70
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff821f1b0a-ffffffff821f1b29: clk_mux_index_to_val.cold (STB_LOCAL)
ffffffff81a95470-ffffffff81a954ea: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffff8000107c62c0)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
Direct callers:
  - drivers/clk/meson/clk-regmap.c:clk_regmap_mux_set_parent
```
**Symbols:**

```
ffff8000107c5cb8-ffff8000107c5d20: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (c08f1570)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
Direct callers:
  - drivers/clk/clk-milbeaut.c:m10v_mux_set_parent
  - drivers/clk/meson/clk-regmap.c:clk_regmap_mux_set_parent
```
**Symbols:**

```
c08f115c-c08f119c: clk_mux_index_to_val (STB_GLOBAL)
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
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffe0005131c2)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffe000512fae-ffffffe000513012: clk_mux_index_to_val (STB_GLOBAL)
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
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8161a662)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff8161a520-ffffffff8161a55e: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8160eb92)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff8160ea50-ffffffff8160ea8e: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81648442)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff81648300-ffffffff8164833e: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int clk_mux_index_to_val(u32 *table, unsigned int flags, u8 index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff816629d2)
Location: drivers/clk/clk-mux.c:69
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
**Symbols:**

```
ffffffff81662890-ffffffff816628ce: clk_mux_index_to_val (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 *table</code> ➡️ <code>const u32 *table</code>
</li>
</ul>
</details>
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
