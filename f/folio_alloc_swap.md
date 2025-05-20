# Function: <code>folio_alloc_swap</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
swp_entry_t folio_alloc_swap(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (0)
Location: mm/swap_slots.c:302
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81e70f87-ffffffff81e7102c: folio_alloc_swap.cold (STB_LOCAL)
ffffffff81383c00-ffffffff81383ec4: folio_alloc_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
swp_entry_t folio_alloc_swap(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (0)
Location: mm/swap_slots.c:302
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff82065d8e-ffffffff82065e32: folio_alloc_swap.cold (STB_LOCAL)
ffffffff814016d0-ffffffff8140192e: folio_alloc_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
swp_entry_t folio_alloc_swap(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (0)
Location: mm/swap_slots.c:302
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff820e5556-ffffffff820e55fa: folio_alloc_swap.cold (STB_LOCAL)
ffffffff814345b0-ffffffff8143480e: folio_alloc_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
swp_entry_t folio_alloc_swap(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (0)
Location: mm/swap_slots.c:302
Inline: False
Direct callers:
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff821c26ff-ffffffff821c27a3: folio_alloc_swap.cold (STB_LOCAL)
ffffffff8146d9b0-ffffffff8146dc08: folio_alloc_swap (STB_GLOBAL)
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
