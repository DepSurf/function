# Function: <code>blk_stat_init</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_stat_init(struct blk_rq_stat *stat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81426d24)
Location: block/blk-stat.c:180
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_clear
  - block/blk-stat.c:blk_stat_clear
  - block/blk-stat.c:blk_stat_clear
  - block/blk-stat.c:blk_stat_clear
  - block/blk-stat.c:blk_queue_stat_get
  - block/blk-stat.c:blk_queue_stat_get
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_show
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_show
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_store
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_store
```
**Symbols:**

```
ffffffff81426b40-ffffffff81426b8c: blk_stat_init (STB_GLOBAL)
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
In block/blk-stat.c (ffffffff8143431a)
Location: block/blk-stat.c:22
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-stat.c:blk_stat_timer_fn
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
In block/blk-stat.c (ffffffff8145ffb0)
Location: block/blk-stat.c:20
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-stat.c:blk_stat_timer_fn
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
In block/blk-stat.c (ffffffff814938ce)
Location: block/blk-stat.c:20
Inline: True
Inline callers:
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-stat.c:blk_stat_timer_fn
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
</ul>
