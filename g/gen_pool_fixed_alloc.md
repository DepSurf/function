# Function: <code>gen_pool_fixed_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8144f120)
Location: lib/genalloc.c:567
Inline: False
```
**Symbols:**

```
ffffffff8144f120-ffffffff8144f184: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8146db20)
Location: lib/genalloc.c:568
Inline: False
```
**Symbols:**

```
ffffffff8146db20-ffffffff8146db84: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81473110)
Location: lib/genalloc.c:568
Inline: False
```
**Symbols:**

```
ffffffff81473110-ffffffff81473163: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814a04a0)
Location: lib/genalloc.c:568
Inline: False
```
**Symbols:**

```
ffffffff814a04a0-ffffffff814a04f3: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814d5640)
Location: lib/genalloc.c:568
Inline: False
```
**Symbols:**

```
ffffffff814d5640-ffffffff814d5690: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814ea110)
Location: lib/genalloc.c:572
Inline: False
```
**Symbols:**

```
ffffffff814ea110-ffffffff814ea160: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
ffffffff81517269-ffffffff8151727f: gen_pool_fixed_alloc.cold (STB_LOCAL)
ffffffff81516fa0-ffffffff81516ff0: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815378b0)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
ffffffff815378b0-ffffffff81537906: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8159ba00)
Location: lib/genalloc.c:689
Inline: False
```
**Symbols:**

```
ffffffff8159ba00-ffffffff8159ba56: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815b7460)
Location: lib/genalloc.c:690
Inline: False
```
**Symbols:**

```
ffffffff815b7460-ffffffff815b74b6: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815c21f0)
Location: lib/genalloc.c:694
Inline: False
```
**Symbols:**

```
ffffffff815c21f0-ffffffff815c2246: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:694
Inline: False
```
**Symbols:**

```
ffffffff81cdb555-ffffffff81cdb593: gen_pool_fixed_alloc.cold (STB_LOCAL)
ffffffff8162a070-ffffffff8162a0f7: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:694
Inline: False
```
**Symbols:**

```
ffffffff81e93d95-ffffffff81e93dd3: gen_pool_fixed_alloc.cold (STB_LOCAL)
ffffffff816fb4f0-ffffffff816fb57d: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:694
Inline: False
```
**Symbols:**

```
ffffffff82078e14-ffffffff82078e52: gen_pool_fixed_alloc.cold (STB_LOCAL)
ffffffff817ee110-ffffffff817ee19d: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:692
Inline: False
```
**Symbols:**

```
ffffffff820f9566-ffffffff820f95a5: gen_pool_fixed_alloc.cold (STB_LOCAL)
ffffffff8182e510-ffffffff8182e59a: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/genalloc.c (0)
Location: lib/genalloc.c:694
Inline: False
```
**Symbols:**

```
ffffffff821d76d3-ffffffff821d7712: gen_pool_fixed_alloc.cold (STB_LOCAL)
ffffffff818800d0-ffffffff8188015a: gen_pool_fixed_alloc (STB_GLOBAL)
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
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffff800010643da8)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
ffff800010643da8-ffff800010643e0c: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c07ea678)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
c07ea678-c07ea6f0: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c0000000007f0150)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
c0000000007f0150-c0000000007f01d4: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffe000470cb6)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
ffffffe000470cb6-ffffffe000470d0a: gen_pool_fixed_alloc (STB_GLOBAL)
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
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152fe90)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
ffffffff8152fe90-ffffffff8152fee6: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81520170)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
ffffffff81520170-ffffffff815201c6: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152bbd0)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
ffffffff8152bbd0-ffffffff8152bc26: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int gen_pool_fixed_alloc(long unsigned int *map, long unsigned int size, long unsigned int start, unsigned int nr, void *data, struct gen_pool *pool, long unsigned int start_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815459d0)
Location: lib/genalloc.c:688
Inline: False
```
**Symbols:**

```
ffffffff815459d0-ffffffff81545a26: gen_pool_fixed_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int start_addr</code>
</li>
</ul>
</details>
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
