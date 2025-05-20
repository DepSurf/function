# Function: <code>folio_lruvec_lock_irqsave</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct lruvec *folio_lruvec_lock_irqsave(struct folio *folio, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d17a0)
Location: mm/memcontrol.c:1262
Inline: False
Direct callers:
  - mm/swap.c:__pagevec_lru_add
  - mm/swap.c:release_pages
  - mm/swap.c:pagevec_lru_move_fn
  - mm/swap.c:__page_cache_release
```
**Symbols:**

```
ffffffff813d17a0-ffffffff813d1831: folio_lruvec_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct lruvec *folio_lruvec_lock_irqsave(struct folio *folio, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81456c30)
Location: mm/memcontrol.c:1342
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:__page_cache_release
```
**Symbols:**

```
ffffffff81456c30-ffffffff81456cc1: folio_lruvec_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct lruvec *folio_lruvec_lock_irqsave(struct folio *folio, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148c490)
Location: mm/memcontrol.c:1366
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:__page_cache_release
```
**Symbols:**

```
ffffffff8148c490-ffffffff8148c521: folio_lruvec_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct lruvec *folio_lruvec_lock_irqsave(struct folio *folio, long unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bbde0)
Location: mm/memcontrol.c:1417
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:folio_batch_move_lru
  - mm/swap.c:__page_cache_release
```
**Symbols:**

```
ffffffff814bbde0-ffffffff814bbe71: folio_lruvec_lock_irqsave (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
