# Function: <code>folio_batch_move_lru</code>

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
void folio_batch_move_lru(struct folio_batch *fbatch, move_fn_t move_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8136f9a0)
Location: mm/swap.c:233
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
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
**Symbols:**

```
ffffffff8136f9a0-ffffffff8136fafd: folio_batch_move_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void folio_batch_move_lru(struct folio_batch *fbatch, move_fn_t move_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a1ac0)
Location: mm/swap.c:203
Inline: False
Direct callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
**Symbols:**

```
ffffffff813a1ac0-ffffffff813a1c39: folio_batch_move_lru (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void folio_batch_move_lru(struct folio_batch *fbatch, move_fn_t move_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813cb750)
Location: mm/swap.c:203
Inline: False
Direct callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:folio_deactivate
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:lru_add_drain_cpu
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_rotate_reclaimable
```
**Symbols:**

```
ffffffff813cb750-ffffffff813cb8c9: folio_batch_move_lru (STB_LOCAL)
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
