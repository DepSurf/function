# Function: <code>_regmap_range_multi_paged_reg_write</code>

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
In drivers/base/regmap/regmap.c (ffffffff81566f21)
Location: drivers/base/regmap/regmap.c:1882
Inline: True
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
In drivers/base/regmap/regmap.c (ffffffff815bb92a)
Location: drivers/base/regmap/regmap.c:1979
Inline: True
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
In drivers/base/regmap/regmap.c (ffffffff815ead3a)
Location: drivers/base/regmap/regmap.c:2025
Inline: True
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
In drivers/base/regmap/regmap.c (ffffffff815ff651)
Location: drivers/base/regmap/regmap.c:2029
Inline: True
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
In drivers/base/regmap/regmap.c (ffffffff81667944)
Location: drivers/base/regmap/regmap.c:2108
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2088
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2187
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2184
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _regmap_range_multi_paged_reg_write(struct regmap *map, struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817de850)
Location: drivers/base/regmap/regmap.c:2186
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
```
**Symbols:**

```
ffffffff817de850-ffffffff817dea27: _regmap_range_multi_paged_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _regmap_range_multi_paged_reg_write(struct regmap *map, struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f3870)
Location: drivers/base/regmap/regmap.c:2335
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
```
**Symbols:**

```
ffffffff817f3870-ffffffff817f3aa9: _regmap_range_multi_paged_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _regmap_range_multi_paged_reg_write(struct regmap *map, struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d80f0)
Location: drivers/base/regmap/regmap.c:2335
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
```
**Symbols:**

```
ffffffff817d80f0-ffffffff817d831b: _regmap_range_multi_paged_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _regmap_range_multi_paged_reg_write(struct regmap *map, struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2376
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
```
**Symbols:**

```
ffffffff818637f0-ffffffff81863a28: _regmap_range_multi_paged_reg_write (STB_LOCAL)
ffffffff81d04bab-ffffffff81d04bd1: _regmap_range_multi_paged_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regmap_range_multi_paged_reg_write(struct regmap *map, struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2396
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
```
**Symbols:**

```
ffffffff819ab940-ffffffff819abba4: _regmap_range_multi_paged_reg_write (STB_LOCAL)
ffffffff81ecd5b6-ffffffff81ecd5dc: _regmap_range_multi_paged_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _regmap_range_multi_paged_reg_write(struct regmap *map, struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2527
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81b1eeb0-ffffffff81b1f114: _regmap_range_multi_paged_reg_write (STB_LOCAL)
ffffffff820992c1-ffffffff820992e7: _regmap_range_multi_paged_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _regmap_range_multi_paged_reg_write(struct regmap *map, struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2544
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81b6e0d0-ffffffff81b6e330: _regmap_range_multi_paged_reg_write (STB_LOCAL)
ffffffff8211a388-ffffffff8211a3af: _regmap_range_multi_paged_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _regmap_range_multi_paged_reg_write(struct regmap *map, struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2432
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81bc1cd0-ffffffff81bc1f30: _regmap_range_multi_paged_reg_write (STB_LOCAL)
ffffffff821f820f-ffffffff821f8236: _regmap_range_multi_paged_reg_write.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000597e64)
Location: drivers/base/regmap/regmap.c:2191
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2191
Inline: True
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
