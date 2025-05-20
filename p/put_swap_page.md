# Function: <code>put_swap_page</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120e090)
Location: mm/swapfile.c:1194
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff8120e090-ffffffff8120e1f2: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81229400)
Location: mm/swapfile.c:1264
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81229400-ffffffff81229689: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124a6e0)
Location: mm/swapfile.c:1264
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8124a6e0-ffffffff8124a95e: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125ecc0)
Location: mm/swapfile.c:1225
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8125ecc0-ffffffff8125efaf: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81279950)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81279950-ffffffff81279c46: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81289430)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81289430-ffffffff81289726: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bc040)
Location: mm/swapfile.c:1362
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812bc040-ffffffff812bc251: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c7b70)
Location: mm/swapfile.c:1380
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812c7b70-ffffffff812c7d7f: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ce4c0)
Location: mm/swapfile.c:1379
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff812ce4c0-ffffffff812ce805: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81313a50)
Location: mm/swapfile.c:1348
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81313a50-ffffffff81313d99: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137f0c0)
Location: mm/swapfile.c:1331
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff8137f0c0-ffffffff8137f465: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010324238)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffff800010324238-ffff8000103243dc: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053bfb0)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
c053bfb0-c053c0bc: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fa0b0)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
c0000000003fa0b0-c0000000003fa2fc: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe0002249b0)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffe0002249b0-ffffffe000224b7e: put_swap_page (STB_GLOBAL)
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
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81281a10)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81281a10-ffffffff81281d06: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81273530)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff81273530-ffffffff81273826: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127f820)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8127f820-ffffffff8127fb16: put_swap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_swap_page(struct page *page, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128f500)
Location: mm/swapfile.c:1325
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:get_swap_page
```
**Symbols:**

```
ffffffff8128f500-ffffffff8128f7ef: put_swap_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
