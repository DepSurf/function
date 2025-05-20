# Function: <code>get_swap_device</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffff8127dafa-ffffffff8127db1e: get_swap_device.cold (STB_LOCAL)
ffffffff812793c0-ffffffff8127941b: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffff8128d57f-ffffffff8128d5a3: get_swap_device.cold (STB_LOCAL)
ffffffff81288ea0-ffffffff81288efb: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff812bc8a5)
Location: mm/swapfile.c:1285
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_count
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
```
**Symbols:**

```
ffffffff812c004b-ffffffff812c006f: get_swap_device.cold (STB_LOCAL)
ffffffff812bbe00-ffffffff812bbe5d: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff812c83b5)
Location: mm/swapfile.c:1303
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_count
Direct callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
```
**Symbols:**

```
ffffffff81be876c-ffffffff81be8790: get_swap_device.cold (STB_LOCAL)
ffffffff812c7910-ffffffff812c7972: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff812ced65)
Location: mm/swapfile.c:1302
Inline: True
Inline callers:
  - mm/swapfile.c:__swap_count
Direct callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
```
**Symbols:**

```
ffffffff81bda763-ffffffff81bda787: get_swap_device.cold (STB_LOCAL)
ffffffff812ce280-ffffffff812ce2e2: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1265
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffff81cbebc6-ffffffff81cbebeb: get_swap_device.cold (STB_LOCAL)
ffffffff81313740-ffffffff81313837: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1247
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffff81e70d49-ffffffff81e70d95: get_swap_device.cold (STB_LOCAL)
ffffffff8137ed90-ffffffff8137ee67: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fd880)
Location: mm/swapfile.c:1251
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffff813fd880-ffffffff813fd9b0: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81430b40)
Location: mm/swapfile.c:1257
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swapfile.c:add_swap_count_continuation
```
**Symbols:**

```
ffffffff81430b40-ffffffff81430c70: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81469f60)
Location: mm/swapfile.c:1257
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swapfile.c:add_swap_count_continuation
```
**Symbols:**

```
ffffffff81469f60-ffffffff8146a090: get_swap_device (STB_GLOBAL)
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
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010323f48)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffff800010323f48-ffff800010323ff4: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053bd5c)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
c053bd5c-c053bde8: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f9ce0)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
c0000000003f9ce0-c0000000003f9d9c: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe00022470c)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffe00022470c-ffffffe0002247a6: get_swap_device (STB_GLOBAL)
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
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffff81285b5f-ffffffff81285b83: get_swap_device.cold (STB_LOCAL)
ffffffff81281480-ffffffff812814db: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffff812779cf-ffffffff812779f3: get_swap_device.cold (STB_LOCAL)
ffffffff812732f0-ffffffff8127334b: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffff8128396f-ffffffff81283993: get_swap_device.cold (STB_LOCAL)
ffffffff8127f290-ffffffff8127f2eb: get_swap_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct swap_info_struct *get_swap_device(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:1249
Inline: False
Direct callers:
  - mm/mincore.c:mincore_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:total_swapcache_pages
  - mm/swapfile.c:add_swap_count_continuation
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swp_swapcount
  - mm/swapfile.c:__swap_count
```
**Symbols:**

```
ffffffff8129365f-ffffffff81293684: get_swap_device.cold (STB_LOCAL)
ffffffff8128ef30-ffffffff8128efb6: get_swap_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
