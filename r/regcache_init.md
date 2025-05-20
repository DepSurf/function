# Function: <code>regcache_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81567820)
Location: drivers/base/regmap/regcache.c:97
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81567820-ffffffff81567bef: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815bc4d0)
Location: drivers/base/regmap/regcache.c:117
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff815bc4d0-ffffffff815bc779: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff815eb8e0)
Location: drivers/base/regmap/regcache.c:117
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff815eb8e0-ffffffff815ebb89: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81600220)
Location: drivers/base/regmap/regcache.c:119
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81600220-ffffffff816004a2: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff81668570)
Location: drivers/base/regmap/regcache.c:119
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81668570-ffffffff816687f5: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816a3ee0)
Location: drivers/base/regmap/regcache.c:119
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff816a3ee0-ffffffff816a4176: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffff816c4a20)
Location: drivers/base/regmap/regcache.c:119
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff816c4a20-ffffffff816c4cb6: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff817005e3-ffffffff8170062f: regcache_init.cold (STB_LOCAL)
ffffffff816ffa10-ffffffff816ffc5e: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff8172493d-ffffffff81724989: regcache_init.cold (STB_LOCAL)
ffffffff81723d90-ffffffff81723fde: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff817e0cfc-ffffffff817e0d48: regcache_init.cold (STB_LOCAL)
ffffffff817e04d0-ffffffff817e070f: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81c0f5d1-ffffffff81c0f61d: regcache_init.cold (STB_LOCAL)
ffffffff817f53c0-ffffffff817f55ff: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81c0171b-ffffffff81c01767: regcache_init.cold (STB_LOCAL)
ffffffff817d9d80-ffffffff817d9fbf: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81d04f93-ffffffff81d0500f: regcache_init.cold (STB_LOCAL)
ffffffff818654c0-ffffffff8186572f: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81ecd9dc-ffffffff81ecda4e: regcache_init.cold (STB_LOCAL)
ffffffff819ad9e0-ffffffff819adc84: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff820995b0-ffffffff820995e0: regcache_init.cold (STB_LOCAL)
ffffffff81b213e0-ffffffff81b216a2: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:113
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff8211a632-ffffffff8211a662: regcache_init.cold (STB_LOCAL)
ffffffff81b705e0-ffffffff81b708e9: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:113
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff821f84b7-ffffffff821f84e7: regcache_init.cold (STB_LOCAL)
ffffffff81bc42e0-ffffffff81bc45e9: regcache_init (STB_GLOBAL)
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
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffff800010918738)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffff800010918738-ffff800010918b90: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c09fe3b8)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
c09fe3b8-c09fe828: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (c0000000009bc060)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
c0000000009bc060-c0000000009bc3c8: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache.c (ffffffe000598d7c)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffe000598d7c-ffffffe000598f70: regcache_init (STB_GLOBAL)
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
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff816eac6d-ffffffff816eacb9: regcache_init.cold (STB_LOCAL)
ffffffff816ea0c0-ffffffff816ea30e: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff816c52ad-ffffffff816c52f9: regcache_init.cold (STB_LOCAL)
ffffffff816c4700-ffffffff816c494e: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff81717dfd-ffffffff81717e49: regcache_init.cold (STB_LOCAL)
ffffffff81717250-ffffffff8171749e: regcache_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int regcache_init(struct regmap *map, const struct regmap_config *config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regcache.c (0)
Location: drivers/base/regmap/regcache.c:115
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_reinit_cache
  - drivers/base/regmap/regmap.c:__regmap_init
```
**Symbols:**

```
ffffffff8173315d-ffffffff817331a9: regcache_init.cold (STB_LOCAL)
ffffffff81732550-ffffffff8173279e: regcache_init (STB_GLOBAL)
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
