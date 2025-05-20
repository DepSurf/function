# Function: <code>zs_malloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81205a30)
Location: mm/zsmalloc.c:1391
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff81205a30-ffffffff81205e51: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122ae40)
Location: mm/zsmalloc.c:1539
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff8122ae40-ffffffff8122b2f0: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123d3b0)
Location: mm/zsmalloc.c:1499
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff8123d3b0-ffffffff8123d848: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81248d40)
Location: mm/zsmalloc.c:1478
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff81248d40-ffffffff81249175: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81268f70)
Location: mm/zsmalloc.c:1482
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff81268f70-ffffffff812693b0: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128df40)
Location: mm/zsmalloc.c:1485
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff8128df40-ffffffff8128e37c: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a3870)
Location: mm/zsmalloc.c:1472
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff812a3870-ffffffff812a3cac: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:1462
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff812bf0fb-ffffffff812bf10e: zs_malloc.cold (STB_LOCAL)
ffffffff812bec80-ffffffff812bf0b4: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d0be0)
Location: mm/zsmalloc.c:1459
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff812d0be0-ffffffff812d1013: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813075a0)
Location: mm/zsmalloc.c:1461
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff813075a0-ffffffff813077a0: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813132e0)
Location: mm/zsmalloc.c:1410
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff813132e0-ffffffff813134e0: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81319430)
Location: mm/zsmalloc.c:1409
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff81319430-ffffffff8131966f: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81365bd0)
Location: mm/zsmalloc.c:1409
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff81365bd0-ffffffff81365e60: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e1140)
Location: mm/zsmalloc.c:1406
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff813e1140-ffffffff813e143e: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81468600)
Location: mm/zsmalloc.c:1560
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff81468600-ffffffff8146890b: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149d5e0)
Location: mm/zsmalloc.c:1360
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff8149d5e0-ffffffff8149d99a: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814ccda0)
Location: mm/zsmalloc.c:1360
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff814ccda0-ffffffff814cd167: zs_malloc (STB_GLOBAL)
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
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffff800010375f68)
Location: mm/zsmalloc.c:1459
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffff800010375f68-ffff80001037643c: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0560a44)
Location: mm/zsmalloc.c:1459
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
c0560a44-c0560ea0: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c000000000465f10)
Location: mm/zsmalloc.c:1459
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
c000000000465f10-c000000000466500: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024e75e)
Location: mm/zsmalloc.c:1459
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffe00024e75e-ffffffe00024eb86: zs_malloc (STB_GLOBAL)
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
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c91c0)
Location: mm/zsmalloc.c:1459
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff812c91c0-ffffffff812c95f3: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812ba200)
Location: mm/zsmalloc.c:1459
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff812ba200-ffffffff812ba633: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c6fd0)
Location: mm/zsmalloc.c:1459
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff812c6fd0-ffffffff812c7403: zs_malloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int zs_malloc(struct zs_pool *pool, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d6880)
Location: mm/zsmalloc.c:1459
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_malloc
```
**Symbols:**

```
ffffffff812d6880-ffffffff812d6ccd: zs_malloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
