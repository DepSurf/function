# Function: <code>folio_lruvec</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8130674c)
Location: include/linux/memcontrol.h:763
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_folio
```
```
In mm/compaction.c (ffffffff81330ae3)
Location: include/linux/memcontrol.h:763
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813366f0)
Location: include/linux/memcontrol.h:763
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/memcontrol.c (ffffffff813d17a5)
Location: include/linux/memcontrol.h:763
Inline: True
Inline callers:
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8137080c)
Location: include/linux/memcontrol.h:745
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_refault
```
```
In mm/compaction.c (ffffffff813a7954)
Location: include/linux/memcontrol.h:745
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813ad95e)
Location: include/linux/memcontrol.h:745
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
```
```
In mm/memcontrol.c (ffffffff81456c35)
Location: include/linux/memcontrol.h:745
Inline: True
Inline callers:
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
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
In mm/swap.c (ffffffff813a29bc)
Location: include/linux/memcontrol.h:758
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_refault
```
```
In mm/compaction.c (ffffffff813daf27)
Location: include/linux/memcontrol.h:758
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813e1e4e)
Location: include/linux/memcontrol.h:758
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:lru_gen_refault
```
```
In mm/memcontrol.c (ffffffff8148c495)
Location: include/linux/memcontrol.h:758
Inline: True
Inline callers:
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
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
In mm/swap.c (ffffffff813cc639)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost_refault
```
```
In mm/compaction.c (ffffffff814050b5)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff8140c67b)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:lru_gen_refault
```
```
In mm/zswap.c (ffffffff81470585)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/zswap.c:zswap_folio_swapin
```
```
In mm/memcontrol.c (ffffffff814bbde5)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memcontrol.c:folio_lruvec_lock_irqsave
  - mm/memcontrol.c:folio_lruvec_lock_irq
  - mm/memcontrol.c:folio_lruvec_lock
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
