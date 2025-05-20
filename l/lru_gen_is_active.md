# Function: <code>lru_gen_is_active</code>

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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136da4a)
Location: include/linux/mm_inline.h:164
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff8137bf4e)
Location: include/linux/mm_inline.h:164
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:drain_evictable
  - mm/vmscan.c:reset_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813a54c8)
Location: include/linux/mm_inline.h:164
Inline: True
```
```
In mm/mlock.c (ffffffff813c1fc8)
Location: include/linux/mm_inline.h:164
Inline: True
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
In mm/swap.c (ffffffff8139fc8e)
Location: include/linux/mm_inline.h:164
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813ab2c5)
Location: include/linux/mm_inline.h:164
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:reset_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff813d8b18)
Location: include/linux/mm_inline.h:164
Inline: True
```
```
In mm/mlock.c (ffffffff813f6918)
Location: include/linux/mm_inline.h:164
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
In mm/swap.c (ffffffff813c98f3)
Location: include/linux/mm_inline.h:165
Inline: True
Inline callers:
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813d4b66)
Location: include/linux/mm_inline.h:165
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:reset_batch_size
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:folio_inc_gen
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/compaction.c (ffffffff81402898)
Location: include/linux/mm_inline.h:165
Inline: True
```
```
In mm/mlock.c (ffffffff81422af8)
Location: include/linux/mm_inline.h:165
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
