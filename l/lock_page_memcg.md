# Function: <code>lock_page_memcg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121df00)
Location: mm/memcontrol.c:1653
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8121df00-ffffffff8121df85: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812304e0)
Location: mm/memcontrol.c:1624
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff812304e0-ffffffff81230565: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123bdd0)
Location: mm/memcontrol.c:1620
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8123bdd0-ffffffff8123be5b: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125b5f0)
Location: mm/memcontrol.c:1634
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8125b5f0-ffffffff8125b67b: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8127f110)
Location: mm/memcontrol.c:1591
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8127f110-ffffffff8127f193: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81293950)
Location: mm/memcontrol.c:1869
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81293950-ffffffff812939d3: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812aef80)
Location: mm/memcontrol.c:2070
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812aef80-ffffffff812af005: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c09e0)
Location: mm/memcontrol.c:2086
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812c09e0-ffffffff812c0a65: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f7100)
Location: mm/memcontrol.c:1960
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812f7100-ffffffff812f7193: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81302560)
Location: mm/memcontrol.c:2149
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81302560-ffffffff813025fc: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308c00)
Location: mm/memcontrol.c:1971
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81308c00-ffffffff81308ca1: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81352980)
Location: mm/memcontrol.c:2023
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/memcontrol.c:mem_cgroup_move_account
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff81352980-ffffffff81352a1e: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d1e20)
Location: mm/memcontrol.c:2076
Inline: False
Direct callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - fs/buffer.c:mark_buffer_dirty
```
**Symbols:**

```
ffffffff813d1e20-ffffffff813d1e7c: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81457520)
Location: mm/memcontrol.c:2136
Inline: False
Direct callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - fs/buffer.c:mark_buffer_dirty
```
**Symbols:**

```
ffffffff81457520-ffffffff8145757c: lock_page_memcg (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103641d8)
Location: mm/memcontrol.c:2086
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffff8000103641d8-ffff800010364304: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0554ab0)
Location: mm/memcontrol.c:2086
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
c0554ab0-c0554b48: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000044ea40)
Location: mm/memcontrol.c:2086
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
c00000000044ea40-c00000000044eb5c: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000241906)
Location: mm/memcontrol.c:2086
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffe000241906-ffffffe00024198a: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b8fc0)
Location: mm/memcontrol.c:2086
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812b8fc0-ffffffff812b9045: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812aa250)
Location: mm/memcontrol.c:2086
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812aa250-ffffffff812aa2d5: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6dd0)
Location: mm/memcontrol.c:2086
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812b6dd0-ffffffff812b6e55: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *lock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c76b0)
Location: mm/memcontrol.c:2086
Inline: True
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812c76b0-ffffffff812c773a: lock_page_memcg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct mem_cgroup *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct mem_cgroup *</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
