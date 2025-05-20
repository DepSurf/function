# Function: <code>_regmap_update_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815653f0)
Location: drivers/base/regmap/regmap.c:2516
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_select_page
  - drivers/base/regmap/regmap.c:regmap_update_bits
  - drivers/base/regmap/regmap.c:regmap_write_bits
  - drivers/base/regmap/regmap.c:regmap_update_bits_async
  - drivers/base/regmap/regmap.c:regmap_update_bits_check
  - drivers/base/regmap/regmap.c:regmap_update_bits_check_async
```
**Symbols:**

```
ffffffff815653f0-ffffffff815654c9: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815b9e60)
Location: drivers/base/regmap/regmap.c:2624
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff815b9e60-ffffffff815b9f39: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e9250)
Location: drivers/base/regmap/regmap.c:2662
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff815e9250-ffffffff815e9329: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fdc20)
Location: drivers/base/regmap/regmap.c:2667
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff815fdc20-ffffffff815fdd01: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81665e10)
Location: drivers/base/regmap/regmap.c:2746
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff81665e10-ffffffff81665ef4: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a1870)
Location: drivers/base/regmap/regmap.c:2701
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff816a1870-ffffffff816a194b: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c2170)
Location: drivers/base/regmap/regmap.c:2861
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff816c2170-ffffffff816c224b: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fd0f0)
Location: drivers/base/regmap/regmap.c:2858
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff816fd0f0-ffffffff816fd1cb: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817214a0)
Location: drivers/base/regmap/regmap.c:2865
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff817214a0-ffffffff8172157b: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817dd400)
Location: drivers/base/regmap/regmap.c:2860
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff817dd400-ffffffff817dd4dc: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f24b0)
Location: drivers/base/regmap/regmap.c:3017
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff817f24b0-ffffffff817f258c: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d6d60)
Location: drivers/base/regmap/regmap.c:3017
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff817d6d60-ffffffff817d6e3c: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff818623b0)
Location: drivers/base/regmap/regmap.c:3058
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff818623b0-ffffffff8186248c: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819aa330)
Location: drivers/base/regmap/regmap.c:3075
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff819aa330-ffffffff819aa423: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3227
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff81b1d640-ffffffff81b1d744: _regmap_update_bits (STB_LOCAL)
ffffffff8209906b-ffffffff82099090: _regmap_update_bits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3257
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff81b6c6b0-ffffffff81b6c7d3: _regmap_update_bits (STB_LOCAL)
ffffffff8211a14d-ffffffff8211a16d: _regmap_update_bits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:3137
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_fields_update_bits_base
  - drivers/base/regmap/regmap.c:regmap_field_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff81bc02e0-ffffffff81bc0403: _regmap_update_bits (STB_LOCAL)
ffffffff821f7ff2-ffffffff821f8012: _regmap_update_bits.cold (STB_LOCAL)
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
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010915ac0)
Location: drivers/base/regmap/regmap.c:2865
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffff800010915ac0-ffff800010915bc8: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fba00)
Location: drivers/base/regmap/regmap.c:2865
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
c09fba00-c09fbb04: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b8210)
Location: drivers/base/regmap/regmap.c:2865
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
c0000000009b8210-c0000000009b83a0: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000596b7c)
Location: drivers/base/regmap/regmap.c:2865
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffe000596b7c-ffffffe000596c3c: _regmap_update_bits (STB_LOCAL)
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
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e77d0)
Location: drivers/base/regmap/regmap.c:2865
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff816e77d0-ffffffff816e78ab: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1e10)
Location: drivers/base/regmap/regmap.c:2865
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff816c1e10-ffffffff816c1eeb: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81714960)
Location: drivers/base/regmap/regmap.c:2865
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff81714960-ffffffff81714a3b: _regmap_update_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int _regmap_update_bits(struct regmap *map, unsigned int reg, unsigned int mask, unsigned int val, bool *change, bool force_write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8172fb70)
Location: drivers/base/regmap/regmap.c:2865
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_update_bits_base
  - drivers/base/regmap/regmap.c:_regmap_select_page
```
**Symbols:**

```
ffffffff8172fb70-ffffffff8172fc4b: _regmap_update_bits (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
