# Function: <code>page_swap_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff811d3360)
Location: mm/swapfile.c:2738
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_set_page_dirty
  - mm/swapfile.c:__page_file_mapping
```
**Symbols:**

```
ffffffff811d3360-ffffffff811d336b: page_swap_info.part.19 (STB_LOCAL)
ffffffff811d71a0-ffffffff811d71c7: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f0da5)
Location: mm/swapfile.c:2724
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff811f5330-ffffffff811f534b: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81201715)
Location: mm/swapfile.c:2736
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81205e60-ffffffff81205e7b: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120c6c5)
Location: mm/swapfile.c:3216
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff812115d0-ffffffff812115eb: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812262f5)
Location: mm/swapfile.c:3470
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff8122bf20-ffffffff8122bf3b: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81248905)
Location: mm/swapfile.c:3494
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff8124e3f0-ffffffff8124e40b: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125cee5)
Location: mm/swapfile.c:3472
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff812627b0-ffffffff812627cb: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81278075)
Location: mm/swapfile.c:3476
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff8127d6a0-ffffffff8127d6c9: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81287b65)
Location: mm/swapfile.c:3484
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff8128d140-ffffffff8128d169: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812b9f25)
Location: mm/swapfile.c:3538
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff812bfbe0-ffffffff812bfc0b: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c5995)
Location: mm/swapfile.c:3558
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff812cb790-ffffffff812cb7bb: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cc645)
Location: mm/swapfile.c:3529
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff812d2330-ffffffff812d235b: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81311975)
Location: mm/swapfile.c:3530
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81317be0-ffffffff81317c23: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137caf5)
Location: mm/swapfile.c:3385
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff81383270-ffffffff813832c3: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fa315)
Location: mm/swapfile.c:3387
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
```
**Symbols:**

```
ffffffff81400c60-ffffffff81400cb3: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142d245)
Location: mm/swapfile.c:3375
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:swap_page_sector
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_fs
```
**Symbols:**

```
ffffffff81433b40-ffffffff81433b93: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010322910)
Location: mm/swapfile.c:3484
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffff800010328898-ffff8000103288f4: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053ae74)
Location: mm/swapfile.c:3484
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
c053fd40-c053fd88: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f8340)
Location: mm/swapfile.c:3484
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
c0000000003ffbc0-c0000000003ffc18: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe0002236e6)
Location: mm/swapfile.c:3484
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffe000228684-ffffffe0002286d6: page_swap_info (STB_GLOBAL)
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
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280145)
Location: mm/swapfile.c:3484
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81285720-ffffffff81285749: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81271fb5)
Location: mm/swapfile.c:3484
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81277590-ffffffff812775b9: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127df55)
Location: mm/swapfile.c:3484
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81283530-ffffffff81283559: page_swap_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct swap_info_struct *page_swap_info(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128db05)
Location: mm/swapfile.c:3484
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
Direct callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
**Symbols:**

```
ffffffff81293210-ffffffff81293239: page_swap_info (STB_GLOBAL)
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
