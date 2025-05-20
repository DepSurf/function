# Function: <code>regcache_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81567680)
Location: drivers/base/regmap/regcache.c:207
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
```
**Symbols:**

```
ffffffff81567680-ffffffff8156775a: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815bc0a0)
Location: drivers/base/regmap/regcache.c:235
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
```
**Symbols:**

```
ffffffff815bc0a0-ffffffff815bc17d: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815eb4b0)
Location: drivers/base/regmap/regcache.c:235
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
  - drivers/base/regmap/regcache-lzo.c:regcache_lzo_sync
```
**Symbols:**

```
ffffffff815eb4b0-ffffffff815eb58d: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815ffdd0)
Location: drivers/base/regmap/regcache.c:237
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff815ffdd0-ffffffff815ffea7: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81668110)
Location: drivers/base/regmap/regcache.c:237
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81668110-ffffffff816681ef: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816a3a80)
Location: drivers/base/regmap/regcache.c:237
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816a3a80-ffffffff816a3b5f: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c45c0)
Location: drivers/base/regmap/regcache.c:237
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816c45c0-ffffffff816c469f: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816ff660)
Location: drivers/base/regmap/regcache.c:233
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816ff660-ffffffff816ff73c: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817239e0)
Location: drivers/base/regmap/regcache.c:233
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817239e0-ffffffff81723abc: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817dfc10)
Location: drivers/base/regmap/regcache.c:233
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817dfc10-ffffffff817dfcec: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817f4b30)
Location: drivers/base/regmap/regcache.c:233
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817f4b30-ffffffff817f4bec: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff817d9440)
Location: drivers/base/regmap/regcache.c:233
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff817d9440-ffffffff817d94fc: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81864b30)
Location: drivers/base/regmap/regcache.c:233
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81864b30-ffffffff81864be9: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff819acfc0)
Location: drivers/base/regmap/regcache.c:233
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff819acfc0-ffffffff819ad0b4: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81b207d0)
Location: drivers/base/regmap/regcache.c:239
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81b207d0-ffffffff81b208c4: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81b6f940)
Location: drivers/base/regmap/regcache.c:237
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81b6f940-ffffffff81b6fa29: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81bc3510)
Location: drivers/base/regmap/regcache.c:237
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_reg_cached
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81bc3510-ffffffff81bc35f9: regcache_read (STB_GLOBAL)
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
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffff8000109184a0)
Location: drivers/base/regmap/regcache.c:233
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffff8000109184a0-ffff8000109185cc: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c09fe1cc)
Location: drivers/base/regmap/regcache.c:233
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
c09fe1cc-c09fe2d4: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c0000000009bb990)
Location: drivers/base/regmap/regcache.c:233
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
c0000000009bb990-c0000000009bbb18: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffe00059898c)
Location: drivers/base/regmap/regcache.c:233
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffe00059898c-ffffffe000598a58: regcache_read (STB_GLOBAL)
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
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816e9d10)
Location: drivers/base/regmap/regcache.c:233
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816e9d10-ffffffff816e9dec: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4350)
Location: drivers/base/regmap/regcache.c:233
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff816c4350-ffffffff816c442c: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81716ea0)
Location: drivers/base/regmap/regcache.c:233
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81716ea0-ffffffff81716f7c: regcache_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int regcache_read(struct regmap *map, unsigned int reg, unsigned int *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81732180)
Location: drivers/base/regmap/regcache.c:233
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:_regmap_read
  - drivers/base/regmap/regmap.c:regmap_cached
  - drivers/base/regmap/regcache.c:regcache_default_sync
```
**Symbols:**

```
ffffffff81732180-ffffffff81732277: regcache_read (STB_GLOBAL)
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
