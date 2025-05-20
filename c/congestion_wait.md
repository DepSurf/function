# Function: <code>congestion_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811ae730)
Location: mm/backing-dev.c:931
Inline: False
Direct callers:
  - mm/page-writeback.c:throttle_vm_writeout
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
```
**Symbols:**

```
ffffffff811ae730-ffffffff811ae84a: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c7b00)
Location: mm/backing-dev.c:950
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:throttle_vm_writeout
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/extents.c:ext4_ext_truncate
```
**Symbols:**

```
ffffffff811c7b00-ffffffff811c7c13: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d7c20)
Location: mm/backing-dev.c:956
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/extents.c:ext4_ext_truncate
```
**Symbols:**

```
ffffffff811d7c20-ffffffff811d7d33: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e0800)
Location: mm/backing-dev.c:1001
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff811e0800-ffffffff811e0913: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f67f0)
Location: mm/backing-dev.c:1016
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_inactive_list
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff811f67f0-ffffffff811f6906: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81217ad0)
Location: mm/backing-dev.c:1014
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81217ad0-ffffffff81217be6: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122a9e0)
Location: mm/backing-dev.c:1017
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8122a9e0-ffffffff8122aaf6: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123a650)
Location: mm/backing-dev.c:1004
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8123a650-ffffffff8123a762: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81248960)
Location: mm/backing-dev.c:1085
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81248960-ffffffff81248a72: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81276ba0)
Location: mm/backing-dev.c:1083
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81276ba0-ffffffff81276cb2: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281490)
Location: mm/backing-dev.c:952
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81281490-ffffffff8128158f: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81286340)
Location: mm/backing-dev.c:951
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81286340-ffffffff8128643f: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c5670)
Location: mm/backing-dev.c:1034
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812c5670-ffffffff812c578e: congestion_wait (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102dd728)
Location: mm/backing-dev.c:1085
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffff8000102dd728-ffff8000102dd878: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c050314c)
Location: mm/backing-dev.c:1085
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
c050314c-c05032cc: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039d300)
Location: mm/backing-dev.c:1085
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
c00000000039d300-c00000000039d494: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f5eae)
Location: mm/backing-dev.c:1085
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffe0001f5eae-ffffffe0001f5fc4: congestion_wait (STB_GLOBAL)
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
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81240fb0)
Location: mm/backing-dev.c:1085
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81240fb0-ffffffff812410c2: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81233fb0)
Location: mm/backing-dev.c:1085
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81233fb0-ffffffff812340c2: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123ed50)
Location: mm/backing-dev.c:1085
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8123ed50-ffffffff8123ee62: congestion_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int congestion_wait(int sync, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124e480)
Location: mm/backing-dev.c:1085
Inline: False
Direct callers:
  - mm/page-writeback.c:do_writepages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:isolate_migratepages_block
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8124e480-ffffffff8124e5a7: congestion_wait (STB_GLOBAL)
```
</details>
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
