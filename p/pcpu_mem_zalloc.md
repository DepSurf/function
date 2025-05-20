# Function: <code>pcpu_mem_zalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b0990)
Location: mm/percpu.c:294
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_extend_area_map
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:percpu_init_late
```
**Symbols:**

```
ffffffff811b0990-ffffffff811b0a03: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811c9bb0)
Location: mm/percpu.c:299
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_extend_area_map
  - mm/percpu.c:percpu_init_late
```
**Symbols:**

```
ffffffff811c9bb0-ffffffff811c9c23: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811d9ca0)
Location: mm/percpu.c:299
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_extend_area_map
  - mm/percpu.c:percpu_init_late
```
**Symbols:**

```
ffffffff811d9ca0-ffffffff811d9d13: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e3350)
Location: mm/percpu.c:286
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
  - mm/percpu.c:pcpu_extend_area_map
  - mm/percpu.c:percpu_init_late
```
**Symbols:**

```
ffffffff811e3350-ffffffff811e3391: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f8b70)
Location: mm/percpu.c:463
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffff811f8b70-ffffffff811f8bcf: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121a570)
Location: mm/percpu.c:461
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffff8121a570-ffffffff8121a5d0: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122d4e0)
Location: mm/percpu.c:469
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffff8122d4e0-ffffffff8122d540: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123d200)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffff8123d200-ffffffff8123d263: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124b650)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffff8124b650-ffffffff8124b6b3: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81279490)
Location: mm/percpu.c:477
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
```
**Symbols:**

```
ffffffff81279490-ffffffff812794d8: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81283cd0)
Location: mm/percpu.c:483
Inline: True
Direct callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
```
**Symbols:**

```
ffffffff81283cd0-ffffffff81283d18: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81288a30)
Location: mm/percpu.c:484
Inline: True
Direct callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81288a30-ffffffff81288a78: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c8380)
Location: mm/percpu.c:508
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
```
**Symbols:**

```
ffffffff812c8380-ffffffff812c83c8: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81325cb0)
Location: mm/percpu.c:508
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
```
**Symbols:**

```
ffffffff81325cb0-ffffffff81325d10: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139a7c0)
Location: mm/percpu.c:504
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
```
**Symbols:**

```
ffffffff8139a7c0-ffffffff8139a820: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cd850)
Location: mm/percpu.c:504
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
```
**Symbols:**

```
ffffffff813cd850-ffffffff813cd8b3: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f81c0)
Location: mm/percpu.c:504
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_reclaim_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_chunk
```
**Symbols:**

```
ffffffff813f81c0-ffffffff813f8223: pcpu_mem_zalloc (STB_LOCAL)
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
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e0d98)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffff8000102e0d98-ffff8000102e0ea4: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0505a74)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
c0505a74-c0505b0c: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a11a0)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
c0000000003a11a0-c0000000003a126c: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f867c)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffe0001f867c-ffffffe0001f86e8: pcpu_mem_zalloc (STB_LOCAL)
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
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81243ca0)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffff81243ca0-ffffffff81243d03: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81236c70)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffff81236c70-ffffffff81236cd3: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81241a40)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffff81241a40-ffffffff81241aa3: pcpu_mem_zalloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *pcpu_mem_zalloc(size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812511e0)
Location: mm/percpu.c:503
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_get_pages
```
**Symbols:**

```
ffffffff812511e0-ffffffff81251243: pcpu_mem_zalloc (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
