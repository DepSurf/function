# Function: <code>kernfs_path_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t kernfs_path_len(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8128a3d0)
Location: fs/kernfs/dir.c:195
Inline: False
Direct callers:
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_writeback_queue_io
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_bdi_dirty_ratelimit
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_work_class
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_write_inode_template
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_wbc_class
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:perf_trace_balance_dirty_pages
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_class
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:perf_trace_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_writeback_queue_io
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_bdi_dirty_ratelimit
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_sb_inodes_requeue
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_work_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_write_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_wbc_class
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
  - fs/fs-writeback.c:trace_event_raw_event_writeback_single_inode_template
```
**Symbols:**

```
ffffffff8128a3d0-ffffffff8128a435: kernfs_path_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t kernfs_path_len(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b7800)
Location: fs/kernfs/dir.c:194
Inline: False
```
**Symbols:**

```
ffffffff812b7800-ffffffff812b7868: kernfs_path_len (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
