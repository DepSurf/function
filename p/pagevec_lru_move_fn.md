# Function: <code>pagevec_lru_move_fn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119dab0)
Location: mm/swap.c:418
Inline: False
Direct callers:
  - mm/swap.c:pagevec_move_tail
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:deactivate_file_page
```
**Symbols:**

```
ffffffff8119dab0-ffffffff8119dbcf: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b2d30)
Location: mm/swap.c:177
Inline: False
Direct callers:
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff811b2d30-ffffffff811b2e11: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c33a0)
Location: mm/swap.c:178
Inline: False
Direct callers:
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff811c33a0-ffffffff811c3481: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cb810)
Location: mm/swap.c:188
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff811cb810-ffffffff811cb8f2: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e0c10)
Location: mm/swap.c:188
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff811e0c10-ffffffff811e0cea: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812024a0)
Location: mm/swap.c:189
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff812024a0-ffffffff81202579: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81214e20)
Location: mm/swap.c:188
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff81214e20-ffffffff81214ef9: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812240d0)
Location: mm/swap.c:189
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff812240d0-ffffffff812241ae: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81231e60)
Location: mm/swap.c:190
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff81231e60-ffffffff81231f3e: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125ea40)
Location: mm/swap.c:206
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff8125ea40-ffffffff8125eb1e: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81268b60)
Location: mm/swap.c:204
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff81268b60-ffffffff81268cac: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8126e900)
Location: mm/swap.c:204
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff8126e900-ffffffff8126ea5b: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812ab960)
Location: mm/swap.c:182
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
```
**Symbols:**

```
ffffffff812ab960-ffffffff812abaa3: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81305850)
Location: mm/swap.c:191
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_rotate_reclaimable
```
**Symbols:**

```
ffffffff81305850-ffffffff81305a76: pagevec_lru_move_fn (STB_LOCAL)
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
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c1b40)
Location: mm/swap.c:190
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffff8000102c1b40-ffff8000102c1ccc: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ecdd0)
Location: mm/swap.c:190
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
c04ecdd0-c04ecebc: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037ba50)
Location: mm/swap.c:190
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
c00000000037ba50-c00000000037bba8: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e2f2c)
Location: mm/swap.c:190
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffe0001e2f2c-ffffffe0001e300e: pagevec_lru_move_fn (STB_LOCAL)
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
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122a4b0)
Location: mm/swap.c:190
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff8122a4b0-ffffffff8122a58e: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121d5d0)
Location: mm/swap.c:190
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff8121d5d0-ffffffff8121d6ae: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228250)
Location: mm/swap.c:190
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff81228250-ffffffff8122832e: pagevec_lru_move_fn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pagevec_lru_move_fn(struct pagevec *pvec, void (*move_fn)(struct page *, struct lruvec *, void *), void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81237590)
Location: mm/swap.c:190
Inline: False
Direct callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:pagevec_move_tail
```
**Symbols:**

```
ffffffff81237590-ffffffff8123766e: pagevec_lru_move_fn (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *arg</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*move_fn)(struct page *, struct lruvec *, void *)</code> ➡️ <code>void (*move_fn)(struct page *, struct lruvec *)</code>
</li>
</ul>
</details>
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
