# Function: <code>regmap_async_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81562b40)
Location: drivers/base/regmap/regmap.c:2731
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81562b40-ffffffff81562d0f: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815b7550)
Location: drivers/base/regmap/regmap.c:2737
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff815b7550-ffffffff815b7703: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815e68a0)
Location: drivers/base/regmap/regmap.c:2775
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff815e68a0-ffffffff815e6a48: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ff9c5)
Location: drivers/base/regmap/regmap.c:2782
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff815fb270-ffffffff815fb3ff: regmap_async_complete.part.23 (STB_LOCAL)
ffffffff815fb400-ffffffff815fb427: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81667ce1)
Location: drivers/base/regmap/regmap.c:2861
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81663430-ffffffff816635c5: regmap_async_complete.part.23 (STB_LOCAL)
ffffffff816635d0-ffffffff816635f7: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a3271)
Location: drivers/base/regmap/regmap.c:2816
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff8169ed50-ffffffff8169eee5: regmap_async_complete.part.23 (STB_LOCAL)
ffffffff8169eef0-ffffffff8169ef17: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3c91)
Location: drivers/base/regmap/regmap.c:2976
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff816bf520-ffffffff816bf6b5: regmap_async_complete.part.25 (STB_LOCAL)
ffffffff816bf6c0-ffffffff816bf6e7: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816feb30)
Location: drivers/base/regmap/regmap.c:2973
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff816fa5d0-ffffffff816fa768: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff816fa770-ffffffff816fa797: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81722f50)
Location: drivers/base/regmap/regmap.c:2980
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff8171e980-ffffffff8171eb18: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff8171eb20-ffffffff8171eb47: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817df0f0)
Location: drivers/base/regmap/regmap.c:2998
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff817db1a0-ffffffff817db338: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff817db340-ffffffff817db367: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817f41c0)
Location: drivers/base/regmap/regmap.c:3155
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff817f0270-ffffffff817f03ec: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff817f03f0-ffffffff817f0417: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817d8a30)
Location: drivers/base/regmap/regmap.c:3155
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff817d4230-ffffffff817d43ac: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff817d43b0-ffffffff817d43d7: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff8186418c)
Location: drivers/base/regmap/regmap.c:3196
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff8185f560-ffffffff8185f6d9: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff8185f6e0-ffffffff8185f707: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff819ac3d2)
Location: drivers/base/regmap/regmap.c:3213
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff819a7b60-ffffffff819a7d39: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff819a7d40-ffffffff819a7d7f: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b1f9e0)
Location: drivers/base/regmap/regmap.c:3367
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81b1ac40-ffffffff81b1ae19: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff81b1ae30-ffffffff81b1ae6f: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81b6ec04)
Location: drivers/base/regmap/regmap.c:3396
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81b69840-ffffffff81b69a19: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff81b69a30-ffffffff81b69a6f: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81bc2804)
Location: drivers/base/regmap/regmap.c:3276
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81bbd500-ffffffff81bbd6d9: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff81bbd6f0-ffffffff81bbd72f: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010917908)
Location: drivers/base/regmap/regmap.c:2980
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffff8000109135f0-ffff800010913800: regmap_async_complete.part.0 (STB_LOCAL)
ffff800010913800-ffff800010913850: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fd77c)
Location: drivers/base/regmap/regmap.c:2980
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
  - sound/soc/soc-io.c:snd_soc_component_async_complete
```
**Symbols:**

```
c09f8d0c-c09f8ef8: regmap_async_complete.part.0 (STB_LOCAL)
c09f8ef8-c09f8f34: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009ba9d0)
Location: drivers/base/regmap/regmap.c:2980
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
c0000000009b4510-c0000000009b4784: regmap_async_complete.part.0 (STB_LOCAL)
c0000000009b4790-c0000000009b47c8: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000598104)
Location: drivers/base/regmap/regmap.c:2980
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffe00059481e-ffffffe0005949a4: regmap_async_complete.part.0 (STB_LOCAL)
ffffffe0005949a4-ffffffe0005949e4: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e9280)
Location: drivers/base/regmap/regmap.c:2980
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff816e4cb0-ffffffff816e4e48: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff816e4e50-ffffffff816e4e77: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c38c0)
Location: drivers/base/regmap/regmap.c:2980
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff816bf2f0-ffffffff816bf488: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff816bf490-ffffffff816bf4b7: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81716410)
Location: drivers/base/regmap/regmap.c:2980
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff81711e40-ffffffff81711fd8: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff81711fe0-ffffffff81712007: regmap_async_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int regmap_async_complete(struct regmap *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817316b0)
Location: drivers/base/regmap/regmap.c:2980
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regcache.c:regcache_sync_region
  - drivers/base/regmap/regcache.c:regcache_sync
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_sync
```
**Symbols:**

```
ffffffff8172cfc0-ffffffff8172d189: regmap_async_complete.part.0 (STB_LOCAL)
ffffffff8172d190-ffffffff8172d1b7: regmap_async_complete (STB_GLOBAL)
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
