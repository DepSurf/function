# Function: <code>release_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr, bool cold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119d800)
Location: mm/swap.c:909
Inline: False
Direct callers:
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__pagevec_release
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff8119d800-ffffffff8119daa5: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr, bool cold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b29b0)
Location: mm/swap.c:729
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff811b29b0-ffffffff811b2d24: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr, bool cold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3040)
Location: mm/swap.c:730
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff811c3040-ffffffff811c3395: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr, bool cold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cb4a0)
Location: mm/swap.c:743
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff811cb4a0-ffffffff811cb810: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e0830)
Location: mm/swap.c:743
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff811e0830-ffffffff811e0c01: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812020b0)
Location: mm/swap.c:715
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff812020b0-ffffffff8120249a: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81214a30)
Location: mm/swap.c:717
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81214a30-ffffffff81214e1f: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81223cd0)
Location: mm/swap.c:718
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff81223cd0-ffffffff812240c5: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81231a60)
Location: mm/swap.c:760
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff81231a60-ffffffff81231e55: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125e620)
Location: mm/swap.c:827
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
```
**Symbols:**

```
ffffffff8125e620-ffffffff8125ea3f: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812686e0)
Location: mm/swap.c:856
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
```
**Symbols:**

```
ffffffff812686e0-ffffffff81268b54: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126e450)
Location: mm/swap.c:895
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
```
**Symbols:**

```
ffffffff8126e450-ffffffff8126e8f7: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812ab450)
Location: mm/swap.c:886
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
```
**Symbols:**

```
ffffffff812ab450-ffffffff812ab952: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81305220)
Location: mm/swap.c:900
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/mlock.c:mlock_pagevec
  - mm/swap_state.c:free_pages_and_swap_cache
```
**Symbols:**

```
ffffffff81305220-ffffffff8130584d: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void release_pages(release_pages_arg arg, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136f470)
Location: mm/swap.c:994
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:folio_batch_move_lru
  - mm/mlock.c:mlock_pagevec
  - mm/swap_state.c:free_pages_and_swap_cache
```
**Symbols:**

```
ffffffff8136f470-ffffffff8136f988: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void release_pages(release_pages_arg arg, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a1590)
Location: mm/swap.c:960
Inline: False
Direct callers:
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:folio_batch_move_lru
  - mm/mlock.c:mlock_folio_batch
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/splice.c:copy_splice_read
  - fs/splice.c:copy_splice_read
```
**Symbols:**

```
ffffffff813a1590-ffffffff813a1aa8: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void release_pages(release_pages_arg arg, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813cb210)
Location: mm/swap.c:960
Inline: False
Direct callers:
  - mm/swap.c:__folio_batch_release
  - mm/swap.c:folio_batch_move_lru
  - mm/mlock.c:mlock_folio_batch
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/splice.c:copy_splice_read
  - fs/splice.c:copy_splice_read
```
**Symbols:**

```
ffffffff813cb210-ffffffff813cb733: release_pages (STB_GLOBAL)
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
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c16f0)
Location: mm/swap.c:760
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffff8000102c16f0-ffff8000102c1b40: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04eca5c)
Location: mm/swap.c:760
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_retrieve
```
**Symbols:**

```
c04eca5c-c04ecdd0: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037b440)
Location: mm/swap.c:760
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
c00000000037b440-c00000000037ba4c: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e2c3a)
Location: mm/swap.c:760
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffe0001e2c3a-ffffffe0001e2f2c: release_pages (STB_GLOBAL)
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
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122a0b0)
Location: mm/swap.c:760
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff8122a0b0-ffffffff8122a4a5: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121d1d0)
Location: mm/swap.c:760
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff8121d1d0-ffffffff8121d5c5: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81227e50)
Location: mm/swap.c:760
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff81227e50-ffffffff81228245: release_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void release_pages(struct page **pages, int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81237190)
Location: mm/swap.c:760
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_release
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap_state.c:free_pages_and_swap_cache
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff81237190-ffffffff81237585: release_pages (STB_GLOBAL)
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
<b>Param removed. </b>
<code>bool cold</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>release_pages_arg arg</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page **pages</code>
</li>
</ul>
</details>
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
