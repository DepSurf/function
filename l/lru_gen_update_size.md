# Function: <code>lru_gen_update_size</code>

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
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void lru_gen_update_size(struct lruvec *lruvec, struct folio *folio, int old_gen, int new_gen);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136d9c1)
Location: include/linux/mm_inline.h:174
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff8137bfb4)
Location: include/linux/mm_inline.h:174
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:lru_gen_add_folio
Direct callers:
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/compaction.c (ffffffff813a5534)
Location: include/linux/mm_inline.h:174
Inline: True
```
```
In mm/mlock.c (ffffffff813c2034)
Location: include/linux/mm_inline.h:174
Inline: True
```
**Symbols:**

```
ffffffff81376450-ffffffff81376b27: lru_gen_update_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8139fc05)
Location: include/linux/mm_inline.h:174
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813ab32b)
Location: include/linux/mm_inline.h:174
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813d8b84)
Location: include/linux/mm_inline.h:174
Inline: True
```
```
In mm/mlock.c (ffffffff813f6984)
Location: include/linux/mm_inline.h:174
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813c9869)
Location: include/linux/mm_inline.h:175
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813d4bcc)
Location: include/linux/mm_inline.h:175
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff81402904)
Location: include/linux/mm_inline.h:175
Inline: True
```
```
In mm/mlock.c (ffffffff81422b64)
Location: include/linux/mm_inline.h:175
Inline: True
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
</ul>
