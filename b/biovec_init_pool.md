# Function: <code>biovec_init_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814799ad)
Location: block/bio.c:1937
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff8147a5d0-ffffffff8147a5f5: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497a0d)
Location: block/bio.c:1869
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff81499e30-ffffffff81499e55: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c53af)
Location: block/bio.c:1903
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff814c7ed0-ffffffff814c7ef5: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de2bf)
Location: block/bio.c:1945
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff814e0fd0-ffffffff814e0ff5: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153ebe5)
Location: block/bio.c:1524
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff8153fb20-ffffffff8153fb45: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155b3f5)
Location: block/bio.c:1527
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff8155c340-ffffffff8155c365: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815634fe)
Location: block/bio.c:1490
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff81564bf0-ffffffff81564c15: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c7dff)
Location: block/bio.c:1574
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff815c8f70-ffffffff815c8f95: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81672b3b)
Location: block/bio.c:1632
Inline: True
Inline callers:
  - block/bio.c:bioset_init
Direct callers:
  - block/bio-integrity.c:bioset_integrity_create
```
**Symbols:**

```
ffffffff816740a0-ffffffff816740d4: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172e5fb)
Location: block/bio.c:1695
Inline: True
Inline callers:
  - block/bio.c:bioset_init
Direct callers:
  - block/bio-integrity.c:bioset_integrity_create
```
**Symbols:**

```
ffffffff8172fd20-ffffffff8172fd54: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176a8cb)
Location: block/bio.c:1680
Inline: True
Inline callers:
  - block/bio.c:bioset_init
Direct callers:
  - block/bio-integrity.c:bioset_integrity_create
```
**Symbols:**

```
ffffffff8176bf50-ffffffff8176bf84: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817acd2b)
Location: block/bio.c:1687
Inline: True
Inline callers:
  - block/bio.c:bioset_init
Direct callers:
  - block/bio-integrity.c:bioset_integrity_create
```
**Symbols:**

```
ffffffff817ae140-ffffffff817ae174: biovec_init_pool (STB_GLOBAL)
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
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105da968)
Location: block/bio.c:1945
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffff8000105ddc08-ffff8000105ddc54: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787cd4)
Location: block/bio.c:1945
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
c078af60-c078afa4: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076aea0)
Location: block/bio.c:1945
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
c00000000076f550-c00000000076f59c: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041df3a)
Location: block/bio.c:1945
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffe000420b6e-ffffffe000420bb8: biovec_init_pool (STB_GLOBAL)
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
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d689f)
Location: block/bio.c:1945
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff814d95b0-ffffffff814d95d5: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c725f)
Location: block/bio.c:1945
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff814c9f60-ffffffff814c9f85: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d292f)
Location: block/bio.c:1945
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff814d5640-ffffffff814d5665: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int biovec_init_pool(mempool_t *pool, int pool_entries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb44f)
Location: block/bio.c:1945
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff814ee250-ffffffff814ee275: biovec_init_pool (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
