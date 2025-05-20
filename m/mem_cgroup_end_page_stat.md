# Function: <code>mem_cgroup_end_page_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_end_page_stat(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fa3c0)
Location: mm/memcontrol.c:1845
Inline: True
Direct callers:
  - mm/page-writeback.c:clear_page_dirty_for_io
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:cancel_dirty_page
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:mark_buffer_dirty
  - fs/buffer.c:mark_buffer_dirty
```
**Symbols:**

```
ffffffff811fa3c0-ffffffff811fa406: mem_cgroup_end_page_stat (STB_GLOBAL)
```
</details>
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
</ul>
