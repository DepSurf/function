# Function: <code>lru_gen_add_folio</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool lru_gen_add_folio(struct lruvec *lruvec, struct folio *folio, bool reclaiming);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: include/linux/mm_inline.h:220
Inline: False
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (0)
Location: include/linux/mm_inline.h:220
Inline: False
Direct callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/mlock.c (0)
Location: include/linux/mm_inline.h:220
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
**Symbols:**

```
ffffffff8136d920-ffffffff8136dd59: lru_gen_add_folio (STB_LOCAL)
ffffffff82062705-ffffffff82062722: lru_gen_add_folio.cold (STB_LOCAL)
ffffffff8137aa80-ffffffff8137aeb9: lru_gen_add_folio (STB_LOCAL)
ffffffff8206296b-ffffffff82062988: lru_gen_add_folio.cold (STB_LOCAL)
ffffffff813c2340-ffffffff813c26f4: lru_gen_add_folio.constprop.0 (STB_LOCAL)
ffffffff82064286-ffffffff820642a3: lru_gen_add_folio.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool lru_gen_add_folio(struct lruvec *lruvec, struct folio *folio, bool reclaiming);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: include/linux/mm_inline.h:220
Inline: False
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (0)
Location: include/linux/mm_inline.h:220
Inline: False
Direct callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/mlock.c (0)
Location: include/linux/mm_inline.h:220
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
**Symbols:**

```
ffffffff8139fb60-ffffffff8139ff77: lru_gen_add_folio (STB_LOCAL)
ffffffff820e1eac-ffffffff820e1ec1: lru_gen_add_folio.cold (STB_LOCAL)
ffffffff813a8d90-ffffffff813a91a7: lru_gen_add_folio (STB_LOCAL)
ffffffff820e202a-ffffffff820e203f: lru_gen_add_folio.cold (STB_LOCAL)
ffffffff813f6c90-ffffffff813f702b: lru_gen_add_folio.constprop.0 (STB_LOCAL)
ffffffff820e3961-ffffffff820e397e: lru_gen_add_folio.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
bool lru_gen_add_folio(struct lruvec *lruvec, struct folio *folio, bool reclaiming);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap.c (0)
Location: include/linux/mm_inline.h:221
Inline: False
Direct callers:
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_add_fn
```
```
In mm/vmscan.c (0)
Location: include/linux/mm_inline.h:221
Inline: False
Direct callers:
  - mm/vmscan.c:check_move_unevictable_folios
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:move_folios_to_lru
```
```
In mm/mlock.c (0)
Location: include/linux/mm_inline.h:221
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_folio
  - mm/mlock.c:__mlock_new_folio
  - mm/mlock.c:__mlock_folio
  - mm/mlock.c:__mlock_folio
```
**Symbols:**

```
ffffffff813c97c0-ffffffff813c9bf8: lru_gen_add_folio (STB_LOCAL)
ffffffff821be8c8-ffffffff821be8e5: lru_gen_add_folio.cold (STB_LOCAL)
ffffffff813d2890-ffffffff813d2cc8: lru_gen_add_folio (STB_LOCAL)
ffffffff821bea3e-ffffffff821bea5b: lru_gen_add_folio.cold (STB_LOCAL)
ffffffff81422e70-ffffffff81423214: lru_gen_add_folio.constprop.0 (STB_LOCAL)
ffffffff821c04e4-ffffffff821c0501: lru_gen_add_folio.constprop.0.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
