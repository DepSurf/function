# Function: <code>blk_mq_cancel_work_sync</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_cancel_work_sync(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815ddf20)
Location: block/blk-mq.c:4021
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:disk_release
```
**Symbols:**

```
ffffffff815ddf20-ffffffff815ddf72: blk_mq_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_cancel_work_sync(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168be80)
Location: block/blk-mq.c:4743
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
  - block/blk-core.c:blk_cleanup_queue
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8168be80-ffffffff8168bf32: blk_mq_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_cancel_work_sync(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8174a480)
Location: block/blk-mq.c:4952
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8174a480-ffffffff8174a52b: blk_mq_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_cancel_work_sync(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81786b60)
Location: block/blk-mq.c:4839
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81786b60-ffffffff81786c0b: blk_mq_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_cancel_work_sync(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c9240)
Location: block/blk-mq.c:4869
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff817c9240-ffffffff817c92eb: blk_mq_cancel_work_sync (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
