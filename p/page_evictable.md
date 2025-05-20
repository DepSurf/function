# Function: <code>page_evictable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a2c50)
Location: mm/vmscan.c:3832
Inline: True
Direct callers:
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff811a2c50-ffffffff811a2c85: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b9310)
Location: mm/vmscan.c:3816
Inline: True
Direct callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff811b9310-ffffffff811b9353: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c9950)
Location: mm/vmscan.c:3827
Inline: True
Direct callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff811c9950-ffffffff811c9990: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d23e0)
Location: mm/vmscan.c:3929
Inline: True
Direct callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff811d23e0-ffffffff811d2420: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e7880)
Location: mm/vmscan.c:3952
Inline: True
Direct callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff811e7880-ffffffff811e78c0: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81208e10)
Location: mm/vmscan.c:3981
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff81208e10-ffffffff81208e50: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121baf0)
Location: mm/vmscan.c:4274
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff8121baf0-ffffffff8121bb30: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122b790)
Location: mm/vmscan.c:4232
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff8122b790-ffffffff8122b7d3: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81239660)
Location: mm/vmscan.c:4318
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff81239660-ffffffff812396a3: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125f457)
Location: mm/internal.h:80
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812658a8)
Location: mm/internal.h:80
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/mlock.c (ffffffff812966ca)
Location: mm/internal.h:80
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81269a55)
Location: mm/internal.h:78
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812701f5)
Location: mm/internal.h:78
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/mlock.c (ffffffff812a163e)
Location: mm/internal.h:78
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126d845)
Location: mm/internal.h:77
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff81275ffd)
Location: mm/internal.h:77
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/mlock.c (ffffffff812a73b2)
Location: mm/internal.h:77
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812a9eb5)
Location: mm/internal.h:77
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
```
```
In mm/vmscan.c (ffffffff812b2652)
Location: mm/internal.h:77
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/mlock.c (ffffffff812e89ef)
Location: mm/internal.h:77
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130f434)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/mlock.c (ffffffff8134ac5a)
Location: mm/internal.h:142
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813c384f)
Location: mm/internal.h:144
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
```
</details>
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
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102ca568)
Location: mm/vmscan.c:4318
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffff8000102ca568-ffff8000102ca5c8: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f43a8)
Location: mm/vmscan.c:4318
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
c04f43a8-c04f43f8: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000387030)
Location: mm/vmscan.c:4318
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
c000000000387030-c0000000003870a8: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e961e)
Location: mm/vmscan.c:4318
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffe0001e961e-ffffffe0001e966c: page_evictable (STB_GLOBAL)
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
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81231cb0)
Location: mm/vmscan.c:4318
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff81231cb0-ffffffff81231cf3: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81224d70)
Location: mm/vmscan.c:4318
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff81224d70-ffffffff81224db3: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122fa50)
Location: mm/vmscan.c:4318
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff8122fa50-ffffffff8122fa93: page_evictable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int page_evictable(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123ee90)
Location: mm/vmscan.c:4318
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
  - mm/mlock.c:__munlock_pagevec
```
**Symbols:**

```
ffffffff8123ee90-ffffffff8123eeea: page_evictable (STB_GLOBAL)
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
