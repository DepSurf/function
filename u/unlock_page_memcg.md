# Function: <code>unlock_page_memcg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121d090)
Location: mm/memcontrol.c:1697
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8121d090-ffffffff8121d0db: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8122f690)
Location: mm/memcontrol.c:1668
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8122f690-ffffffff8122f6db: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123c0d0)
Location: mm/memcontrol.c:1690
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8123c0d0-ffffffff8123c11b: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125b920)
Location: mm/memcontrol.c:1704
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8125b920-ffffffff8125b970: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8127f440)
Location: mm/memcontrol.c:1661
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff8127f440-ffffffff8127f48c: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81293d30)
Location: mm/memcontrol.c:1939
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap.c:iomap_set_page_dirty
  - fs/iomap.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81293d30-ffffffff81293d7c: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5260)
Location: mm/memcontrol.c:2140
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812b5260-ffffffff812b5274: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6d50)
Location: mm/memcontrol.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812c6d50-ffffffff812c6d64: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f6ac0)
Location: mm/memcontrol.c:2031
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812f6ac0-ffffffff812f6b18: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81301f30)
Location: mm/memcontrol.c:2226
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81301f30-ffffffff81301f97: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81307ab0)
Location: mm/memcontrol.c:2035
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff81307ab0-ffffffff81307b25: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81351f00)
Location: mm/memcontrol.c:2087
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:do_page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffff81351f00-ffffffff81351f75: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d1f00)
Location: mm/memcontrol.c:2108
Inline: False
Direct callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/huge_memory.c:__split_huge_pmd_locked
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
```
**Symbols:**

```
ffffffff813d1f00-ffffffff813d1f5b: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81457620)
Location: mm/memcontrol.c:2168
Inline: False
Direct callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
```
**Symbols:**

```
ffffffff81457620-ffffffff8145767b: unlock_page_memcg (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369b20)
Location: mm/memcontrol.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffff800010369b20-ffff800010369b4c: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055ae80)
Location: mm/memcontrol.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
c055ae80-c055aea0: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0000000004585f0)
Location: mm/memcontrol.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
c0000000004585f0-c000000000458608: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002473b4)
Location: mm/memcontrol.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
**Symbols:**

```
ffffffe0002473b4-ffffffe0002473de: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf330)
Location: mm/memcontrol.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812bf330-ffffffff812bf344: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0420)
Location: mm/memcontrol.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812b0420-ffffffff812b0434: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd140)
Location: mm/memcontrol.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812bd140-ffffffff812bd154: unlock_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unlock_page_memcg(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cd990)
Location: mm/memcontrol.c:2156
Inline: False
Direct callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__cancel_dirty_page
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
  - fs/iomap/buffered-io.c:iomap_set_page_dirty
```
**Symbols:**

```
ffffffff812cd990-ffffffff812cd9a4: unlock_page_memcg (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
