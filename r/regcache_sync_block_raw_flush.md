# Function: <code>regcache_sync_block_raw_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815674f0)
Location: drivers/base/regmap/regcache.c:657
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff815674f0-ffffffff815675da: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815bbf10)
Location: drivers/base/regmap/regcache.c:706
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff815bbf10-ffffffff815bbffe: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815eb320)
Location: drivers/base/regmap/regcache.c:706
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff815eb320-ffffffff815eb40e: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815ffc60)
Location: drivers/base/regmap/regcache.c:708
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff815ffc60-ffffffff815ffd3f: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81667fa0)
Location: drivers/base/regmap/regcache.c:708
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff81667fa0-ffffffff8166807f: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816a3900)
Location: drivers/base/regmap/regcache.c:708
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff816a3900-ffffffff816a39df: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4440)
Location: drivers/base/regmap/regcache.c:708
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff816c4440-ffffffff816c451f: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff816ff500-ffffffff816ff5be: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff81700516-ffffffff81700540: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff81723880-ffffffff8172393e: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff81724870-ffffffff8172489a: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw
```
**Symbols:**

```
ffffffff817df8a0-ffffffff817df95f: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff817e0be8-ffffffff817e0c12: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw
  - drivers/base/regmap/regcache.c:regcache_sync_block_raw
```
**Symbols:**

```
ffffffff817f47f0-ffffffff817f48af: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff81c0f4be-ffffffff81c0f4e8: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff817d9060-ffffffff817d911f: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff81c01608-ffffffff81c01632: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff818647f0-ffffffff818648ac: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff81d04da0-ffffffff81d04dca: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff819acad0-ffffffff819acbb3: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff81ecd7e1-ffffffff81ecd80b: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81b20220)
Location: drivers/base/regmap/regcache.c:711
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff81b20220-ffffffff81b20326: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81b6f470)
Location: drivers/base/regmap/regcache.c:725
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff81b6f470-ffffffff81b6f576: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81bc3040)
Location: drivers/base/regmap/regcache.c:762
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff81bc3040-ffffffff81bc3146: regcache_sync_block_raw_flush (STB_LOCAL)
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
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffff800010918040)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffff800010918040-ffff800010918144: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c09fe030)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
c09fe030-c09fe124: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c0000000009bb750)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
c0000000009bb750-c0000000009bb8a0: regcache_sync_block_raw_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffe00059882c)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffe00059882c-ffffffe0005988f6: regcache_sync_block_raw_flush (STB_LOCAL)
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
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff816e9bb0-ffffffff816e9c6e: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff816eaba0-ffffffff816eabca: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff816c41f0-ffffffff816c42ae: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff816c51e0-ffffffff816c520a: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff81716d40-ffffffff81716dfe: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff81717d30-ffffffff81717d5a: regcache_sync_block_raw_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regcache_sync_block_raw_flush(struct regmap *map, const void **data, unsigned int base, unsigned int cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:704
Inline: False
Direct callers:
  - drivers/base/regmap/regcache.c:regcache_sync_block
  - drivers/base/regmap/regcache.c:regcache_sync_block
```
**Symbols:**

```
ffffffff81732020-ffffffff817320de: regcache_sync_block_raw_flush (STB_LOCAL)
ffffffff81733090-ffffffff817330ba: regcache_sync_block_raw_flush.cold (STB_LOCAL)
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
