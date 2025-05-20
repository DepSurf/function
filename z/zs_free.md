# Function: <code>zs_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff81205fc0)
Location: mm/zsmalloc.c:1467
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_zpool_free
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff81205fc0-ffffffff812060a2: zs_free.part.20 (STB_LOCAL)
ffffffff812060b0-ffffffff812060c6: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122bba0)
Location: mm/zsmalloc.c:1620
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff8122bba0-ffffffff8122bcc4: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123e100)
Location: mm/zsmalloc.c:1580
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff8123e100-ffffffff8123e220: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81249aa0)
Location: mm/zsmalloc.c:1559
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff81249aa0-ffffffff81249bc3: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81269d00)
Location: mm/zsmalloc.c:1563
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff81269d00-ffffffff81269e23: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128e690)
Location: mm/zsmalloc.c:1566
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff8128e690-ffffffff8128e7b3: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a3200)
Location: mm/zsmalloc.c:1553
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff812a3200-ffffffff812a3323: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812be560)
Location: mm/zsmalloc.c:1543
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff812be560-ffffffff812be68f: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d0450)
Location: mm/zsmalloc.c:1540
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff812d0450-ffffffff812d057f: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81306bb0)
Location: mm/zsmalloc.c:1542
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff81306bb0-ffffffff81306cd1: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81312740)
Location: mm/zsmalloc.c:1491
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff81312740-ffffffff81312861: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81318c60)
Location: mm/zsmalloc.c:1490
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff81318c60-ffffffff81318dc7: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81365240)
Location: mm/zsmalloc.c:1489
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff81365240-ffffffff813653cb: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e0e90)
Location: mm/zsmalloc.c:1491
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff813e0e90-ffffffff813e0fb6: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:1659
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff82068512-ffffffff82068535: zs_free.cold (STB_LOCAL)
ffffffff81468060-ffffffff814681b4: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149d310)
Location: mm/zsmalloc.c:1445
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff8149d310-ffffffff8149d429: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814ccad0)
Location: mm/zsmalloc.c:1448
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff814ccad0-ffffffff814ccbe9: zs_free (STB_GLOBAL)
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
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffff8000103755e0)
Location: mm/zsmalloc.c:1540
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffff8000103755e0-ffff800010375824: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c05620a8)
Location: mm/zsmalloc.c:1540
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
c05620a8-c05622c4: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c000000000468860)
Location: mm/zsmalloc.c:1540
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
c000000000468860-c000000000468aa4: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024dffe)
Location: mm/zsmalloc.c:1540
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffe00024dffe-ffffffe00024e17a: zs_free (STB_GLOBAL)
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
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c8a30)
Location: mm/zsmalloc.c:1540
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff812c8a30-ffffffff812c8b5f: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812b9a70)
Location: mm/zsmalloc.c:1540
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff812b9a70-ffffffff812b9b9f: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c6840)
Location: mm/zsmalloc.c:1540
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff812c6840-ffffffff812c696f: zs_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void zs_free(struct zs_pool *pool, long unsigned int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d7fb0)
Location: mm/zsmalloc.c:1540
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_zpool_free
```
**Symbols:**

```
ffffffff812d7fb0-ffffffff812d810e: zs_free (STB_GLOBAL)
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
