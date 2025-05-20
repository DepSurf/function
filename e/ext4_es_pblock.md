# Function: <code>ext4_es_pblock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:143
Inline: True
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/extents_status.h:143
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:143
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812cde84)
Location: fs/ext4/extents_status.h:143
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff812dcedc)
Location: fs/ext4/extents_status.h:143
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
```
In fs/ext4/extents_status.c (ffffffff8130b242)
Location: fs/ext4/extents_status.h:143
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812e3c74)
Location: fs/ext4/extents_status.h:143
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff812f2a2a)
Location: fs/ext4/extents_status.h:143
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
```
In fs/ext4/extents_status.c (ffffffff81321242)
Location: fs/ext4/extents_status.h:143
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812f0239)
Location: fs/ext4/extents_status.h:143
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff81307e7d)
Location: fs/ext4/extents_status.h:143
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_get_next_extent
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff81327578)
Location: fs/ext4/extents_status.h:143
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81314d49)
Location: fs/ext4/extents_status.h:144
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813222eb)
Location: fs/ext4/extents_status.h:144
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff8134ba5e)
Location: fs/ext4/extents_status.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81342b6b)
Location: fs/ext4/extents_status.h:144
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff81351388)
Location: fs/ext4/extents_status.h:144
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff81379864)
Location: fs/ext4/extents_status.h:144
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135a63b)
Location: fs/ext4/extents_status.h:206
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8136a22b)
Location: fs/ext4/extents_status.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff81392814)
Location: fs/ext4/extents_status.h:206
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81383642)
Location: fs/ext4/extents_status.h:206
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8139408b)
Location: fs/ext4/extents_status.h:206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff813bc6cb)
Location: fs/ext4/extents_status.h:206
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81391734)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8139bc98)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813aca1d)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff813d599b)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dd214)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813e76e2)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff813f8cc9)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff8142209c)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813eeb04)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813f99a2)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff8140b4b8)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff8143873c)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fd3f0)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
```
In fs/ext4/extents_status.c (ffffffff813ffd4b)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff81411673)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff8143e8ec)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81447369)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81452366)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff81464449)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff8149256c)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c3aa2)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff814cf2af)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff814e3805)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff8151737b)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
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
In fs/ext4/extents.c (ffffffff8155bde2)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81567b6f)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff8157cd05)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff815b2e98)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
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
In fs/ext4/extents.c (ffffffff81593bf8)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8159f0ff)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff815b4154)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff815e9bf8)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cc8e8)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff815d7c62)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff815ecf54)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff816225e8)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff8000104643d0)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffff80001046ea90)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffff8000104811f0)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffff8000104b712c)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c06253cc)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c0630044)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (c06422c0)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (c0670740)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000582514)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c00000000058ed38)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (c0000000005a5740)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (c0000000005de58c)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f31f0)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffe0002fb862)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffe000309eb2)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffe00032c7b8)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389d14)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81394278)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a4ffd)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff813cdf7b)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a7a4)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81384d08)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff81395a8d)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff813be9fb)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81387674)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81391bd8)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a285d)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff813cb40b)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139b354)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813a5ab8)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813b6f3d)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
```
In fs/ext4/super.c (ffffffff813e065b)
Location: fs/ext4/extents_status.h:207
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
</ul>

## Differences
