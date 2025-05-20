# Function: <code>swapcache_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void swapcache_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d47a0)
Location: mm/swapfile.c:852
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:add_to_swap
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff811d47a0-ffffffff811d47df: swapcache_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void swapcache_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f2670)
Location: mm/swapfile.c:847
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff811f2670-ffffffff811f26af: swapcache_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void swapcache_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81203070)
Location: mm/swapfile.c:853
Inline: False
Direct callers:
  - mm/vmscan.c:__remove_mapping
  - mm/shmem.c:shmem_writepage
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:add_to_swap
```
**Symbols:**

```
ffffffff81203070-ffffffff812030af: swapcache_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120e0ac)
Location: mm/swapfile.c:1152
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81229523)
Location: mm/swapfile.c:1187
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124a701)
Location: mm/swapfile.c:1187
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
