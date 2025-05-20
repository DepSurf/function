# Function: <code>_regmap_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815652f0)
Location: drivers/base/regmap/regmap.c:1473
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
```
**Symbols:**

```
ffffffff815652f0-ffffffff815653ee: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815b9d60)
Location: drivers/base/regmap/regmap.c:1581
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
```
**Symbols:**

```
ffffffff815b9d60-ffffffff815b9e53: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e9150)
Location: drivers/base/regmap/regmap.c:1627
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
```
**Symbols:**

```
ffffffff815e9150-ffffffff815e9243: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815fdb30)
Location: drivers/base/regmap/regmap.c:1630
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff815fdb30-ffffffff815fdc1c: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81665d10)
Location: drivers/base/regmap/regmap.c:1709
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81665d10-ffffffff81665e09: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a1770)
Location: drivers/base/regmap/regmap.c:1725
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816a1770-ffffffff816a1869: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c2070)
Location: drivers/base/regmap/regmap.c:1763
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816c2070-ffffffff816c2169: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fcff0)
Location: drivers/base/regmap/regmap.c:1760
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816fcff0-ffffffff816fd0e8: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817213a0)
Location: drivers/base/regmap/regmap.c:1767
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817213a0-ffffffff81721498: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817dd300)
Location: drivers/base/regmap/regmap.c:1762
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_single
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817dd300-ffffffff817dd3f9: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f23a0)
Location: drivers/base/regmap/regmap.c:1908
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block_single
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817f23a0-ffffffff817f24a7: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d6c50)
Location: drivers/base/regmap/regmap.c:1908
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817d6c50-ffffffff817d6d57: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1949
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81d04910-ffffffff81d04955: _regmap_write.cold (STB_LOCAL)
ffffffff81862280-ffffffff818623a3: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1968
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81ecd2c2-ffffffff81ecd301: _regmap_write.cold (STB_LOCAL)
ffffffff819aa1e0-ffffffff819aa323: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1972
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff8209902c-ffffffff8209906b: _regmap_write.cold (STB_LOCAL)
ffffffff81b1d4e0-ffffffff81b1d623: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1990
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_val
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache-maple.c:regcache_maple_sync_block
```
**Symbols:**

```
ffffffff8211a10e-ffffffff8211a14d: _regmap_write.cold (STB_LOCAL)
ffffffff81b6c550-ffffffff81b6c693: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:1898
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_update_bits
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_val
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache-maple.c:regcache_maple_sync_block
```
**Symbols:**

```
ffffffff821f7fb3-ffffffff821f7ff2: _regmap_write.cold (STB_LOCAL)
ffffffff81bc0180-ffffffff81bc02c3: _regmap_write (STB_GLOBAL)
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
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010915998)
Location: drivers/base/regmap/regmap.c:1767
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffff800010915998-ffff800010915ac0: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fb8d4)
Location: drivers/base/regmap/regmap.c:1767
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
c09fb8d4-c09fba00: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009b8070)
Location: drivers/base/regmap/regmap.c:1767
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
c0000000009b8070-c0000000009b8208: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000596a9a)
Location: drivers/base/regmap/regmap.c:1767
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffe000596a9a-ffffffe000596b7c: _regmap_write (STB_GLOBAL)
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
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e76d0)
Location: drivers/base/regmap/regmap.c:1767
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816e76d0-ffffffff816e77c8: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c1d10)
Location: drivers/base/regmap/regmap.c:1767
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816c1d10-ffffffff816c1e08: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81714860)
Location: drivers/base/regmap/regmap.c:1767
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81714860-ffffffff81714958: _regmap_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _regmap_write(struct regmap *map, unsigned int reg, unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8172fa60)
Location: drivers/base/regmap/regmap.c:1767
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_bulk_write
  - drivers/base/regmap/regmap.c:regmap_write_async
  - drivers/base/regmap/regmap.c:regmap_write
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff8172fa60-ffffffff8172fb70: _regmap_write (STB_GLOBAL)
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
