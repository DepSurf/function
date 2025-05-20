# Function: <code>regcache_cache_bypass</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81567440)
Location: drivers/base/regmap/regcache.c:512
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff81567440-ffffffff815674e3: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815bbe70)
Location: drivers/base/regmap/regcache.c:540
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff815bbe70-ffffffff815bbf0a: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815eb280)
Location: drivers/base/regmap/regcache.c:540
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff815eb280-ffffffff815eb31a: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815ffbc0)
Location: drivers/base/regmap/regcache.c:542
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff815ffbc0-ffffffff815ffc56: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81667f00)
Location: drivers/base/regmap/regcache.c:542
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff81667f00-ffffffff81667f99: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816a3850)
Location: drivers/base/regmap/regcache.c:542
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff816a3850-ffffffff816a38e9: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4390)
Location: drivers/base/regmap/regcache.c:542
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff816c4390-ffffffff816c4429: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff81700503-ffffffff81700516: regcache_cache_bypass.cold (STB_LOCAL)
ffffffff816ff460-ffffffff816ff4f9: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817237e0)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff817237e0-ffffffff81723879: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817df960)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff817df960-ffffffff817df9f9: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817f48b0)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff817f48b0-ffffffff817f4940: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817d91b0)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff817d91b0-ffffffff817d9240: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff81d04ddf-ffffffff81d04df4: regcache_cache_bypass.cold (STB_LOCAL)
ffffffff81864940-ffffffff818649d0: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff81ecd80b-ffffffff81ecd820: regcache_cache_bypass.cold (STB_LOCAL)
ffffffff819acbc0-ffffffff819acc71: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:545
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff820994be-ffffffff820994d3: regcache_cache_bypass.cold (STB_LOCAL)
ffffffff81b20380-ffffffff81b20431: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:551
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff8211a55a-ffffffff8211a56f: regcache_cache_bypass.cold (STB_LOCAL)
ffffffff81b6f5d0-ffffffff81b6f681: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:580
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff821f83e0-ffffffff821f83f5: regcache_cache_bypass.cold (STB_LOCAL)
ffffffff81bc31a0-ffffffff81bc3251: regcache_cache_bypass (STB_GLOBAL)
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
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffff800010918238)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffff800010918238-ffff800010918318: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c09fdf4c)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
c09fdf4c-c09fe030: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c0000000009bb610)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
c0000000009bb610-c0000000009bb748: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffe000598718)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffe000598718-ffffffe0005987c6: regcache_cache_bypass (STB_GLOBAL)
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
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816e9b10)
Location: drivers/base/regmap/regcache.c:538
Inline: False
```
**Symbols:**

```
ffffffff816e9b10-ffffffff816e9ba9: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4150)
Location: drivers/base/regmap/regcache.c:538
Inline: False
```
**Symbols:**

```
ffffffff816c4150-ffffffff816c41e9: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81716ca0)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff81716ca0-ffffffff81716d39: regcache_cache_bypass (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void regcache_cache_bypass(struct regmap *map, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81731f70)
Location: drivers/base/regmap/regcache.c:538
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_set_regcache_bypass
```
**Symbols:**

```
ffffffff81731f70-ffffffff8173201e: regcache_cache_bypass (STB_GLOBAL)
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
