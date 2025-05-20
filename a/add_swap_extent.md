# Function: <code>add_swap_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d5ae0)
Location: mm/swapfile.c:1695
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
```
**Symbols:**

```
ffffffff811d5ae0-ffffffff811d5bc0: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f4d7a)
Location: mm/swapfile.c:1682
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
```
**Symbols:**

```
ffffffff811f3b90-ffffffff811f3c78: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812058e7)
Location: mm/swapfile.c:1701
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
```
**Symbols:**

```
ffffffff812046c0-ffffffff812047a8: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81210fe2)
Location: mm/swapfile.c:2133
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
```
**Symbols:**

```
ffffffff8120fd30-ffffffff8120fe19: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8122855c)
Location: mm/swapfile.c:2346
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
```
**Symbols:**

```
ffffffff8122bce0-ffffffff8122bdc9: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124dde0)
Location: mm/swapfile.c:2346
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - fs/iomap.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff8124cfa0-ffffffff8124d085: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812621c8)
Location: mm/swapfile.c:2320
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - fs/iomap.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff8125d2f0-ffffffff8125d3d5: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812785b0)
Location: mm/swapfile.c:2311
Inline: True
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff812785b0-ffffffff812786a6: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812880a0)
Location: mm/swapfile.c:2311
Inline: True
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff812880a0-ffffffff81288196: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ba230)
Location: mm/swapfile.c:2341
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:setup_swap_extents
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff812ba230-ffffffff812ba326: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c5ca0)
Location: mm/swapfile.c:2357
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:setup_swap_extents
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff812c5ca0-ffffffff812c5d96: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cc720)
Location: mm/swapfile.c:2328
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:setup_swap_map_and_extents
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff812cc720-ffffffff812cc813: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81311a90)
Location: mm/swapfile.c:2315
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:setup_swap_map_and_extents
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff81311a90-ffffffff81311b83: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137cc30)
Location: mm/swapfile.c:2185
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:setup_swap_map_and_extents
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff8137cc30-ffffffff8137cd3e: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fa7c0)
Location: mm/swapfile.c:2187
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:setup_swap_map_and_extents
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff813fa7c0-ffffffff813fa8ce: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142d810)
Location: mm/swapfile.c:2178
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:setup_swap_map_and_extents
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff8142d810-ffffffff8142d91d: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff814672a0)
Location: mm/swapfile.c:2186
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:setup_swap_map_and_extents
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff814672a0-ffffffff814673e0: add_swap_extent (STB_GLOBAL)
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
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010322f78)
Location: mm/swapfile.c:2311
Inline: True
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffff800010322f78-ffff800010323060: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053b2bc)
Location: mm/swapfile.c:2311
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
c053b2bc-c053b3a4: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f8dd0)
Location: mm/swapfile.c:2311
Inline: False
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
c0000000003f8dd0-c0000000003f8f44: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000223a9e)
Location: mm/swapfile.c:2311
Inline: True
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffe000223a9e-ffffffe000223b56: add_swap_extent (STB_GLOBAL)
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
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280680)
Location: mm/swapfile.c:2311
Inline: True
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff81280680-ffffffff81280776: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812724f0)
Location: mm/swapfile.c:2311
Inline: True
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff812724f0-ffffffff812725e6: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127e490)
Location: mm/swapfile.c:2311
Inline: True
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff8127e490-ffffffff8127e586: add_swap_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int add_swap_extent(struct swap_info_struct *sis, long unsigned int start_page, long unsigned int nr_pages, sector_t start_block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128e820)
Location: mm/swapfile.c:2311
Inline: True
Direct callers:
  - mm/page_io.c:generic_swapfile_activate
  - mm/swapfile.c:__do_sys_swapon
  - fs/iomap/swapfile.c:iomap_swapfile_add_extent
```
**Symbols:**

```
ffffffff8128e820-ffffffff8128e916: add_swap_extent (STB_GLOBAL)
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
