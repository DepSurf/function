# Function: <code>__probestub_balance_dirty_pages</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __probestub_balance_dirty_pages(void *__data, struct bdi_writeback *wb, long unsigned int thresh, long unsigned int bg_thresh, long unsigned int dirty, long unsigned int bdi_thresh, long unsigned int bdi_dirty, long unsigned int dirty_ratelimit, long unsigned int task_ratelimit, long unsigned int dirtied, long unsigned int period, long int pause, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814efe60)
Location: include/trace/events/writeback.h:621
Inline: False
```
**Symbols:**

```
ffffffff814efe60-ffffffff814efe6f: __probestub_balance_dirty_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __probestub_balance_dirty_pages(void *__data, struct bdi_writeback *wb, long unsigned int thresh, long unsigned int bg_thresh, long unsigned int dirty, long unsigned int bdi_thresh, long unsigned int bdi_dirty, long unsigned int dirty_ratelimit, long unsigned int task_ratelimit, long unsigned int dirtied, long unsigned int period, long int pause, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81524570)
Location: include/trace/events/writeback.h:621
Inline: False
```
**Symbols:**

```
ffffffff81524570-ffffffff8152457f: __probestub_balance_dirty_pages (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
