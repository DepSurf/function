# Function: <code>xa_store_range</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a190d0)
Location: lib/xarray.c:1569
Inline: False
Direct callers:
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages
  - kernel/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff81a190d0-ffffffff81a19382: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a88de0)
Location: lib/xarray.c:1547
Inline: False
Direct callers:
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages
  - mm/memremap.c:devm_memremap_pages_release
```
**Symbols:**

```
ffffffff81a88de0-ffffffff81a8909d: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac0080)
Location: lib/xarray.c:1558
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81ac0080-ffffffff81ac033d: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fbdc0)
Location: lib/xarray.c:1560
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff815fbdc0-ffffffff815fc079: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620960)
Location: lib/xarray.c:1710
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pageunmap_range
```
**Symbols:**

```
ffffffff81620960-ffffffff81620c19: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81604140)
Location: lib/xarray.c:1711
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81604140-ffffffff816043f9: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1711
Inline: False
Direct callers:
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81ce009b-ffffffff81ce00dd: xa_store_range.cold (STB_LOCAL)
ffffffff816729b0-ffffffff81672ca3: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81ea67fa-ffffffff81ea6840: xa_store_range.cold (STB_LOCAL)
ffffffff8178d280-ffffffff8178d56a: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1718
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff820b8080-ffffffff820b80d8: xa_store_range.cold (STB_LOCAL)
ffffffff8204a8d0-ffffffff8204abb7: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1716
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff82139461-ffffffff821394b9: xa_store_range.cold (STB_LOCAL)
ffffffff820c91d0-ffffffff820c94bb: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1716
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:pagemap_range
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff8221b206-ffffffff8221b25e: xa_store_range.cold (STB_LOCAL)
ffffffff821a3b50-ffffffff821a3e3b: xa_store_range (STB_GLOBAL)
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
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9ad40)
Location: lib/xarray.c:1558
Inline: False
```
**Symbols:**

```
ffff800010d9ad40-ffff800010d9b080: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee1f10)
Location: lib/xarray.c:1558
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
c000000000ee1f10-c000000000ee2348: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5eed0)
Location: lib/xarray.c:1558
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81a5eed0-ffffffff81a5f18d: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1bfa0)
Location: lib/xarray.c:1558
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81a1bfa0-ffffffff81a1c25d: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81acb2c0)
Location: lib/xarray.c:1558
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81acb2c0-ffffffff81acb57d: xa_store_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xa_store_range(struct xarray *xa, long unsigned int first, long unsigned int last, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad7920)
Location: lib/xarray.c:1558
Inline: False
Direct callers:
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memremap_pages
  - mm/memremap.c:memunmap_pages
```
**Symbols:**

```
ffffffff81ad7920-ffffffff81ad7bdb: xa_store_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
