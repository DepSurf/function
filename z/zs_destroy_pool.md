# Function: <code>zs_destroy_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812050c0)
Location: mm/zsmalloc.c:1973
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_destroy
  - mm/zsmalloc.c:zs_create_pool
```
**Symbols:**

```
ffffffff812050c0-ffffffff81205197: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122a130)
Location: mm/zsmalloc.c:2495
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff8122a130-ffffffff8122a223: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123c680)
Location: mm/zsmalloc.c:2455
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff8123c680-ffffffff8123c773: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812482b0)
Location: mm/zsmalloc.c:2428
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff812482b0-ffffffff812483a2: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81268470)
Location: mm/zsmalloc.c:2442
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff81268470-ffffffff81268562: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2465
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff8128edce-ffffffff8128ede6: zs_destroy_pool.cold.47 (STB_LOCAL)
ffffffff8128ce00-ffffffff8128cec4: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2465
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff812a3cd3-ffffffff812a3ceb: zs_destroy_pool.cold.47 (STB_LOCAL)
ffffffff812a1d80-ffffffff812a1e44: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2515
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff812bf0e3-ffffffff812bf0fb: zs_destroy_pool.cold (STB_LOCAL)
ffffffff812bd010-ffffffff812bd169: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff812d1043-ffffffff812d105b: zs_destroy_pool.cold (STB_LOCAL)
ffffffff812cef00-ffffffff812cf059: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2519
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff813077c6-ffffffff813077df: zs_destroy_pool.cold (STB_LOCAL)
ffffffff81305210-ffffffff81305375: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2473
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff81bea372-ffffffff81bea38b: zs_destroy_pool.cold (STB_LOCAL)
ffffffff81310f70-ffffffff813110d5: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2470
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff81bdc3a9-ffffffff81bdc3c2: zs_destroy_pool.cold (STB_LOCAL)
ffffffff81317040-ffffffff813171a5: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2470
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff81cc34eb-ffffffff81cc350b: zs_destroy_pool.cold (STB_LOCAL)
ffffffff813634a0-ffffffff8136369f: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2346
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff81e75b66-ffffffff81e75b86: zs_destroy_pool.cold (STB_LOCAL)
ffffffff813e0200-ffffffff813e035c: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81467120)
Location: mm/zsmalloc.c:2530
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff81467120-ffffffff81467256: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149c700)
Location: mm/zsmalloc.c:2307
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff8149c700-ffffffff8149c83d: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cbe50)
Location: mm/zsmalloc.c:2288
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff814cbe50-ffffffff814cbf8d: zs_destroy_pool (STB_GLOBAL)
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
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffff800010373b30)
Location: mm/zsmalloc.c:2517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffff800010373b30-ffff800010373ca4: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0560328)
Location: mm/zsmalloc.c:2517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
c0560328-c05604a0: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c000000000466850)
Location: mm/zsmalloc.c:2517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
c000000000466850-c000000000466a50: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024ca32)
Location: mm/zsmalloc.c:2517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffe00024ca32-ffffffe00024cb98: zs_destroy_pool (STB_GLOBAL)
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
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff812c9623-ffffffff812c963b: zs_destroy_pool.cold (STB_LOCAL)
ffffffff812c74e0-ffffffff812c7639: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff812ba663-ffffffff812ba67b: zs_destroy_pool.cold (STB_LOCAL)
ffffffff812b8520-ffffffff812b8679: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff812c7433-ffffffff812c744b: zs_destroy_pool.cold (STB_LOCAL)
ffffffff812c52f0-ffffffff812c5449: zs_destroy_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void zs_destroy_pool(struct zs_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2517
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_zpool_destroy
```
**Symbols:**

```
ffffffff812d8120-ffffffff812d8138: zs_destroy_pool.cold (STB_LOCAL)
ffffffff812d5dd0-ffffffff812d5f24: zs_destroy_pool (STB_GLOBAL)
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
