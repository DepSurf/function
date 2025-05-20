# Function: <code>blk_queue_start_drain</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_start_drain(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cce58)
Location: block/blk-core.c:339
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:blk_mark_disk_dead
```
**Symbols:**

```
ffffffff815ce410-ffffffff815ce44c: blk_queue_start_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_start_drain(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678536)
Location: block/blk-core.c:273
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:blk_mark_disk_dead
```
**Symbols:**

```
ffffffff81678630-ffffffff81678678: blk_queue_start_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_start_drain(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81734a80)
Location: block/blk-core.c:294
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/genhd.c:del_gendisk
  - block/genhd.c:blk_mark_disk_dead
```
**Symbols:**

```
ffffffff81734a80-ffffffff81734aca: blk_queue_start_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_start_drain(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81770fd0)
Location: block/blk-core.c:291
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/genhd.c:blk_mark_disk_dead
```
**Symbols:**

```
ffffffff81770fd0-ffffffff8177101a: blk_queue_start_drain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_start_drain(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b3320)
Location: block/blk-core.c:293
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_destroy_queue
  - block/genhd.c:__blk_mark_disk_dead
```
**Symbols:**

```
ffffffff817b3320-ffffffff817b336a: blk_queue_start_drain (STB_GLOBAL)
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
