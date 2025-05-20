# Function: <code>swp_swap_info</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812262f5)
Location: mm/swapfile.c:3465
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swapin_readahead
```
**Symbols:**

```
ffffffff8122bf00-ffffffff8122bf17: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81248905)
Location: mm/swapfile.c:3489
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff8124e3d0-ffffffff8124e3e7: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125cee5)
Location: mm/swapfile.c:3467
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81262790-ffffffff812627a7: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81278075)
Location: mm/swapfile.c:3471
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffffffff8127d670-ffffffff8127d695: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81287b65)
Location: mm/swapfile.c:3479
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffffffff8128d110-ffffffff8128d135: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812b9f25)
Location: mm/swapfile.c:3533
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffffffff812bfbb0-ffffffff812bfbd8: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c5995)
Location: mm/swapfile.c:3553
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffffffff812cb760-ffffffff812cb788: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cc645)
Location: mm/swapfile.c:3524
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff812d2300-ffffffff812d2328: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81311975)
Location: mm/swapfile.c:3525
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81317ba0-ffffffff81317bdf: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137caf5)
Location: mm/swapfile.c:3380
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81383220-ffffffff8138326f: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fa315)
Location: mm/swapfile.c:3382
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81400c00-ffffffff81400c4f: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142d245)
Location: mm/swapfile.c:3370
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81433ae0-ffffffff81433b2f: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff814669e5)
Location: mm/swapfile.c:3381
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_folio_sector
Direct callers:
  - mm/page_io.c:swap_read_folio
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff8146cf90-ffffffff8146cfdf: swp_swap_info (STB_GLOBAL)
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
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010322910)
Location: mm/swapfile.c:3479
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffff800010328840-ffff800010328898: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053ae74)
Location: mm/swapfile.c:3479
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
c053fcfc-c053fd40: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f8340)
Location: mm/swapfile.c:3479
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
c0000000003ffb70-c0000000003ffbb8: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe0002236e6)
Location: mm/swapfile.c:3479
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffffffe000228634-ffffffe000228684: swp_swap_info (STB_GLOBAL)
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
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280145)
Location: mm/swapfile.c:3479
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffffffff812856f0-ffffffff81285715: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81271fb5)
Location: mm/swapfile.c:3479
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffffffff81277560-ffffffff81277585: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127df55)
Location: mm/swapfile.c:3479
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffffffff81283500-ffffffff81283525: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *swp_swap_info(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128db05)
Location: mm/swapfile.c:3479
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
**Symbols:**

```
ffffffff812931e0-ffffffff81293205: swp_swap_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
