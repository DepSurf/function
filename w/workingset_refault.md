# Function: <code>workingset_refault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool workingset_refault(void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811b9e90)
Location: mm/workingset.c:231
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff811b9e90-ffffffff811b9f26: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool workingset_refault(void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811d4260)
Location: mm/workingset.c:232
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff811d4260-ffffffff811d432a: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool workingset_refault(void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811e42a0)
Location: mm/workingset.c:233
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff811e42a0-ffffffff811e4371: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool workingset_refault(void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811ee680)
Location: mm/workingset.c:234
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff811ee680-ffffffff811ee7dc: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool workingset_refault(void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81204af0)
Location: mm/workingset.c:235
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff81204af0-ffffffff81204c4c: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool workingset_refault(void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff812258a0)
Location: mm/workingset.c:235
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff812258a0-ffffffff81225ae1: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81238e60)
Location: mm/workingset.c:250
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff81238e60-ffffffff812391a2: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8124a060)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff8124a060-ffffffff8124a1f5: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff812584b0)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff812584b0-ffffffff81258645: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81286b70)
Location: mm/workingset.c:281
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff81286b70-ffffffff81286e58: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81290de0)
Location: mm/workingset.c:282
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff81290de0-ffffffff8129113c: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81296440)
Location: mm/workingset.c:282
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff81296440-ffffffff81296732: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:284
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff81cbbd29-ffffffff81cbbd55: workingset_refault.cold (STB_LOCAL)
ffffffff812d6bd0-ffffffff812d6ea4: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void workingset_refault(struct folio *folio, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:285
Inline: False
Direct callers:
  - mm/filemap.c:filemap_add_folio
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff81e6d9d2-ffffffff81e6d9ee: workingset_refault.cold (STB_LOCAL)
ffffffff81336340-ffffffff813366a2: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void workingset_refault(struct folio *folio, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:385
Inline: False
Direct callers:
  - mm/filemap.c:filemap_add_folio
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff82063ce5-ffffffff82063d09: workingset_refault.cold (STB_LOCAL)
ffffffff813ad5c0-ffffffff813ad909: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void workingset_refault(struct folio *folio, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:508
Inline: False
Direct callers:
  - mm/filemap.c:filemap_add_folio
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff820e33f8-ffffffff820e340d: workingset_refault.cold (STB_LOCAL)
ffffffff813e1c60-ffffffff813e1df1: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void workingset_refault(struct folio *folio, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:529
Inline: False
Direct callers:
  - mm/filemap.c:filemap_add_folio
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff821bfe54-ffffffff821bfe69: workingset_refault.cold (STB_LOCAL)
ffffffff8140c4a0-ffffffff8140c62d: workingset_refault (STB_GLOBAL)
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
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffff8000102f02a0)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffff8000102f02a0-ffff8000102f0464: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (c05139a8)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
c05139a8-c0513b14: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (c0000000003b4c70)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
c0000000003b4c70-c0000000003b4eb8: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffe000203cb8)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffe000203cb8-ffffffe000203e10: workingset_refault (STB_GLOBAL)
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
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81250b00)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff81250b00-ffffffff81250c95: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81243a80)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff81243a80-ffffffff81243bd3: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8124e8a0)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff8124e8a0-ffffffff8124ea35: workingset_refault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void workingset_refault(struct page *page, void *shadow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8125e210)
Location: mm/workingset.c:249
Inline: False
Direct callers:
  - mm/filemap.c:add_to_page_cache_lru
```
**Symbols:**

```
ffffffff8125e210-ffffffff8125e3af: workingset_refault (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param reordered. </b>
<code>shadow</code> ➡️ <code>page, shadow</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
