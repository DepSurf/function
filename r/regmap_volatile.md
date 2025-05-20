# Function: <code>regmap_volatile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81565220)
Location: drivers/base/regmap/regmap.c:115
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_read_file
```
**Symbols:**

```
ffffffff81565220-ffffffff81565287: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815b9c90)
Location: drivers/base/regmap/regmap.c:116
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff815b9c90-ffffffff815b9cf7: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e9080)
Location: drivers/base/regmap/regmap.c:139
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff815e9080-ffffffff815e90e7: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fda60)
Location: drivers/base/regmap/regmap.c:139
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff815fda60-ffffffff815fdac4: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81665c40)
Location: drivers/base/regmap/regmap.c:140
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff81665c40-ffffffff81665ca7: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a1610)
Location: drivers/base/regmap/regmap.c:140
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff816a1610-ffffffff816a167d: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1e90)
Location: drivers/base/regmap/regmap.c:150
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff816c1e90-ffffffff816c1efd: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fce10)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff816fce10-ffffffff816fce74: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817211c0)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff817211c0-ffffffff81721224: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817dd150)
Location: drivers/base/regmap/regmap.c:147
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff817dd150-ffffffff817dd1b4: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f21f0)
Location: drivers/base/regmap/regmap.c:147
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff817f21f0-ffffffff817f2254: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d6aa0)
Location: drivers/base/regmap/regmap.c:147
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff817d6aa0-ffffffff817d6b04: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff818620d0)
Location: drivers/base/regmap/regmap.c:147
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff818620d0-ffffffff81862134: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819a9fd0)
Location: drivers/base/regmap/regmap.c:147
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff819a9fd0-ffffffff819aa05c: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b1d290)
Location: drivers/base/regmap/regmap.c:147
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff81b1d290-ffffffff81b1d31c: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b6c300)
Location: drivers/base/regmap/regmap.c:147
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff81b6c300-ffffffff81b6c38c: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bbff30)
Location: drivers/base/regmap/regmap.c:147
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_bulk_read
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_raw_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_read
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff81bbff30-ffffffff81bbffbc: regmap_volatile (STB_GLOBAL)
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
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010915718)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffff800010915718-ffff8000109157b4: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fb6f8)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regcache.c:regcache_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
c09fb6f8-c09fb778: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b7ce0)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_read
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
c0000000009b7ce0-c0000000009b7dc8: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe00059688c)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffe00059688c-ffffffe000596904: regmap_volatile (STB_GLOBAL)
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
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e74f0)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff816e74f0-ffffffff816e7554: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1b30)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff816c1b30-ffffffff816c1b94: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81714680)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff81714680-ffffffff817146e4: regmap_volatile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool regmap_volatile(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8172f880)
Location: drivers/base/regmap/regmap.c:146
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_noinc_read
  - drivers/base/regmap/regmap.c:regmap_noinc_write
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regmap.c:regmap_volatile_range
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_write
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regcache.c:regcache_hw_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_show
```
**Symbols:**

```
ffffffff8172f880-ffffffff8172f8e4: regmap_volatile (STB_GLOBAL)
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
