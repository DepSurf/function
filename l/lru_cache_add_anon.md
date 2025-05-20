# Function: <code>lru_cache_add_anon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - mm/shmem.c:shmem_replace_page
  - mm/shmem.c:shmem_getpage_gfp
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff8119dea0-ffffffff8119deb0: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:405
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811b36c0-ffffffff811b36d0: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (0)
Location: mm/swap.c:406
Inline: False
Direct callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811c3d40-ffffffff811c3d50: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cc0f0)
Location: mm/swap.c:417
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811cc0f0-ffffffff811cc129: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e10e0)
Location: mm/swap.c:417
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff811e10e0-ffffffff811e1119: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81202960)
Location: mm/swap.c:418
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81202960-ffffffff81202999: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812152e0)
Location: mm/swap.c:412
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_replace_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff812152e0-ffffffff81215319: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81224d10)
Location: mm/swap.c:413
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81224d10-ffffffff81224d49: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81232aa0)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81232aa0-ffffffff81232ad9: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c2998)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffff8000102c2998-ffff8000102c2a1c: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04edb88)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
c04edb88-c04edbe0: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037cb10)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
c00000000037cb10-c00000000037cb88: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e3d14)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffe0001e3d14-ffffffe0001e3d6e: lru_cache_add_anon (STB_GLOBAL)
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
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122b0f0)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8122b0f0-ffffffff8122b129: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121e200)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8121e200-ffffffff8121e239: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228e90)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81228e90-ffffffff81228ec9: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lru_cache_add_anon(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81238250)
Location: mm/swap.c:414
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81238250-ffffffff81238289: lru_cache_add_anon (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
