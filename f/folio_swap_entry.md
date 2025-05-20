# Function: <code>folio_swap_entry</code>

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
In mm/vmscan.c (ffffffff8130cdba)
Location: include/linux/swap.h:348
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81318692)
Location: include/linux/swap.h:348
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/util.c (0)
Location: include/linux/swap.h:348
Inline: True
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
In mm/vmscan.c (ffffffff8137626e)
Location: include/linux/swap.h:344
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8138c5e5)
Location: include/linux/swap.h:344
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/util.c (0)
Location: include/linux/swap.h:344
Inline: True
```
```
In mm/swap_state.c (ffffffff813f8d85)
Location: include/linux/swap.h:344
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff813fe60f)
Location: include/linux/swap.h:344
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
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
In mm/vmscan.c (ffffffff813a629b)
Location: include/linux/swap.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff813bec13)
Location: include/linux/swap.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
```
```
In mm/util.c (0)
Location: include/linux/swap.h:340
Inline: True
```
```
In mm/swap_state.c (ffffffff8142bb55)
Location: include/linux/swap.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff814315a5)
Location: include/linux/swap.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
