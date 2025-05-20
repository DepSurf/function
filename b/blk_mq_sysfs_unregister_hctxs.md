# Function: <code>blk_mq_sysfs_unregister_hctxs</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blk_mq_sysfs_unregister_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-sysfs.c (0)
Location: block/blk-mq-sysfs.c:299
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8207685f-ffffffff82076873: blk_mq_sysfs_unregister_hctxs.cold (STB_LOCAL)
ffffffff8174d560-ffffffff8174d67d: blk_mq_sysfs_unregister_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blk_mq_sysfs_unregister_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-sysfs.c (0)
Location: block/blk-mq-sysfs.c:273
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff820f66e1-ffffffff820f66f5: blk_mq_sysfs_unregister_hctxs.cold (STB_LOCAL)
ffffffff81789b80-ffffffff81789c9d: blk_mq_sysfs_unregister_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_mq_sysfs_unregister_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-sysfs.c (0)
Location: block/blk-mq-sysfs.c:273
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff821d3c06-ffffffff821d3c1a: blk_mq_sysfs_unregister_hctxs.cold (STB_LOCAL)
ffffffff817cc300-ffffffff817cc41d: blk_mq_sysfs_unregister_hctxs (STB_GLOBAL)
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
