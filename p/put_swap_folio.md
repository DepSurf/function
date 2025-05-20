# Function: <code>put_swap_folio</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void put_swap_folio(struct folio *folio, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fdc30)
Location: mm/swapfile.c:1335
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff813fdc30-ffffffff813fdf8f: put_swap_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void put_swap_folio(struct folio *folio, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81430cd0)
Location: mm/swapfile.c:1341
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff81430cd0-ffffffff81430f6d: put_swap_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void put_swap_folio(struct folio *folio, swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146a0f0)
Location: mm/swapfile.c:1341
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
  - mm/swap_slots.c:folio_alloc_swap
```
**Symbols:**

```
ffffffff8146a0f0-ffffffff8146a38a: put_swap_folio (STB_GLOBAL)
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
