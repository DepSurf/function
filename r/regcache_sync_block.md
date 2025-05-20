# Function: <code>regcache_sync_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81568260)
Location: drivers/base/regmap/regcache.c:727
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81568260-ffffffff815684be: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815bcdf0)
Location: drivers/base/regmap/regcache.c:776
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff815bcdf0-ffffffff815bd067: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815ec200)
Location: drivers/base/regmap/regcache.c:776
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff815ec200-ffffffff815ec477: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81600b00)
Location: drivers/base/regmap/regcache.c:778
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81600b00-ffffffff81600d5e: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81668e70)
Location: drivers/base/regmap/regcache.c:778
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81668e70-ffffffff816690ce: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816a47f0)
Location: drivers/base/regmap/regcache.c:778
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff816a47f0-ffffffff816a4a5c: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c5330)
Location: drivers/base/regmap/regcache.c:778
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff816c5330-ffffffff816c559c: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81700676-ffffffff81700696: regcache_sync_block.cold (STB_LOCAL)
ffffffff81700290-ffffffff817004f0: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff817249d0-ffffffff817249f0: regcache_sync_block.cold (STB_LOCAL)
ffffffff81724610-ffffffff81724870: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817e0b70)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff817e0b70-ffffffff817e0be8: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817f5a60)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff817f5a60-ffffffff817f5ad8: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81c01767-ffffffff81c01787: regcache_sync_block.cold (STB_LOCAL)
ffffffff817da040-ffffffff817da290: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81d0500f-ffffffff81d0508a: regcache_sync_block.cold (STB_LOCAL)
ffffffff818657b0-ffffffff81865ace: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81ecda4e-ffffffff81ecda82: regcache_sync_block.cold (STB_LOCAL)
ffffffff819add20-ffffffff819adf73: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:781
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff820995e0-ffffffff820995f5: regcache_sync_block.cold (STB_LOCAL)
ffffffff81b21760-ffffffff81b219c7: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:795
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff8211a662-ffffffff8211a677: regcache_sync_block.cold (STB_LOCAL)
ffffffff81b70a50-ffffffff81b70c55: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:832
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff821f84e7-ffffffff821f84fc: regcache_sync_block.cold (STB_LOCAL)
ffffffff81bc4750-ffffffff81bc4955: regcache_sync_block (STB_GLOBAL)
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
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffff800010919370)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffff800010919370-ffff800010919610: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c09fefc0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
c09fefc0-c09ff280: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c0000000009bce50)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
c0000000009bce50-c0000000009bd218: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffe0005995b0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffe0005995b0-ffffffe0005997c4: regcache_sync_block (STB_GLOBAL)
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
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff816ead00-ffffffff816ead20: regcache_sync_block.cold (STB_LOCAL)
ffffffff816ea940-ffffffff816eaba0: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff816c5340-ffffffff816c5360: regcache_sync_block.cold (STB_LOCAL)
ffffffff816c4f80-ffffffff816c51e0: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81717e90-ffffffff81717eb0: regcache_sync_block.cold (STB_LOCAL)
ffffffff81717ad0-ffffffff81717d30: regcache_sync_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block(struct regmap *map, void *block, long unsigned int *cache_present, unsigned int block_base, unsigned int start, unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:774
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff817331f0-ffffffff81733210: regcache_sync_block.cold (STB_LOCAL)
ffffffff81732e30-ffffffff81733090: regcache_sync_block (STB_GLOBAL)
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
