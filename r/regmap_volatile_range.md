# Function: <code>regmap_volatile_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815659ea)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ba5a9)
Location: drivers/base/regmap/regmap.c:147
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e99a9)
Location: drivers/base/regmap/regmap.c:170
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fe376)
Location: drivers/base/regmap/regmap.c:170
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816665a6)
Location: drivers/base/regmap/regmap.c:171
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a1680)
Location: drivers/base/regmap/regmap.c:171
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffff816a1680-ffffffff816a1707: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1f00)
Location: drivers/base/regmap/regmap.c:203
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffff816c1f00-ffffffff816c1f85: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fce80)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffff816fce80-ffffffff816fcf05: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81721230)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffff81721230-ffffffff817212b5: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817de4eb)
Location: drivers/base/regmap/regmap.c:200
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f350b)
Location: drivers/base/regmap/regmap.c:200
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d7d8b)
Location: drivers/base/regmap/regmap.c:200
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8186346b)
Location: drivers/base/regmap/regmap.c:200
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819ab57d)
Location: drivers/base/regmap/regmap.c:200
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b1ea0f)
Location: drivers/base/regmap/regmap.c:200
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b6dc5f)
Location: drivers/base/regmap/regmap.c:200
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bc186f)
Location: drivers/base/regmap/regmap.c:200
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
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
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff8000109157b8)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffff8000109157b8-ffff800010915844: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fb778)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
c09fb778-c09fb7dc: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b7dd0)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
c0000000009b7dd0-c0000000009b7eb4: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000596904)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffe000596904-ffffffe000596996: regmap_volatile_range (STB_LOCAL)
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
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e7560)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffff816e7560-ffffffff816e75e5: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1ba0)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffff816c1ba0-ffffffff816c1c25: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817146f0)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffff817146f0-ffffffff81714775: regmap_volatile_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool regmap_volatile_range(struct regmap *map, unsigned int reg, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8172f8f0)
Location: drivers/base/regmap/regmap.c:199
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
```
**Symbols:**

```
ffffffff8172f8f0-ffffffff8172f975: regmap_volatile_range (STB_LOCAL)
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
