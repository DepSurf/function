# Function: <code>folio_memcg_lock</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void folio_memcg_lock(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff813d0767)
Location: mm/memcontrol.c:2032
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:lock_page_memcg
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:lock_page_memcg
  - fs/buffer.c:block_dirty_folio
```
**Symbols:**

```
ffffffff813c9c60-ffffffff813c9d04: folio_memcg_lock.part.0 (STB_LOCAL)
ffffffff813d1df0-ffffffff813d1e18: folio_memcg_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void folio_memcg_lock(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81455e40)
Location: mm/memcontrol.c:2092
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:lock_page_memcg
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:lock_page_memcg
  - fs/buffer.c:block_dirty_folio
```
**Symbols:**

```
ffffffff8144f220-ffffffff8144f2c4: folio_memcg_lock.part.0 (STB_LOCAL)
ffffffff814574e0-ffffffff81457508: folio_memcg_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void folio_memcg_lock(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148cd40)
Location: mm/memcontrol.c:2112
Inline: True
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
**Symbols:**

```
ffffffff8148cd40-ffffffff8148cded: folio_memcg_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void folio_memcg_lock(struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bc680)
Location: mm/memcontrol.c:2184
Inline: True
Direct callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_cancel_dirty
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:block_dirty_folio
```
**Symbols:**

```
ffffffff814bc680-ffffffff814bc72d: folio_memcg_lock (STB_GLOBAL)
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
