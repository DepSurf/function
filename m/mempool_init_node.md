# Function: <code>mempool_init_node</code>

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
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811f1020)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff811f1020-ffffffff811f10f8: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81202e80)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff81202e80-ffffffff81202f58: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121a270)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff8121a270-ffffffff8121a35c: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81227be0)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff81227be0-ffffffff81227ccc: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81254550)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff81254550-ffffffff81254631: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8125f160)
Location: mm/mempool.c:178
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff8125f160-ffffffff8125f241: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81263cd0)
Location: mm/mempool.c:178
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff81263cd0-ffffffff81263dae: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812a02b0)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff812a02b0-ffffffff812a038e: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812f78b0)
Location: mm/mempool.c:179
Inline: False
Direct callers:
  - mm/mempool.c:mempool_create
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff812f78b0-ffffffff812f79a4: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81361240)
Location: mm/mempool.c:185
Inline: False
Direct callers:
  - mm/mempool.c:mempool_create
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff81361240-ffffffff8136132c: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81393600)
Location: mm/mempool.c:185
Inline: False
Direct callers:
  - mm/mempool.c:mempool_create
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff81393600-ffffffff813936ec: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813bd2b0)
Location: mm/mempool.c:195
Inline: False
Direct callers:
  - mm/mempool.c:mempool_create
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff813bd2b0-ffffffff813bd39c: mempool_init_node (STB_GLOBAL)
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
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffff8000102b5168)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffff8000102b5168-ffff8000102b528c: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c04e24ec)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
c04e24ec-c04e25e4: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c00000000036c620)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
c00000000036c620-c00000000036c7ac: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffe0001da220)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffe0001da220-ffffffe0001da2ee: mempool_init_node (STB_GLOBAL)
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
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81220230)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff81220230-ffffffff8122031c: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812133e0)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff812133e0-ffffffff812134cc: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121dfd0)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff8121dfd0-ffffffff8121e0bc: mempool_init_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mempool_init_node(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data, gfp_t gfp_mask, int node_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8122d040)
Location: mm/mempool.c:180
Inline: True
Direct callers:
  - mm/mempool.c:mempool_create_node
  - mm/mempool.c:mempool_init
```
**Symbols:**

```
ffffffff8122d040-ffffffff8122d12c: mempool_init_node (STB_GLOBAL)
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
