# Function: <code>elv_bio_merged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_bio_merged(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3ef0)
Location: block/elevator.c:529
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff813b3ef0-ffffffff813b3f0e: elv_bio_merged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_bio_merged(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7bd0)
Location: block/elevator.c:528
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff813f7bd0-ffffffff813f7bee: elv_bio_merged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_bio_merged(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411600)
Location: block/elevator.c:526
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff81411600-ffffffff8141161e: elv_bio_merged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elv_bio_merged(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141f1c0)
Location: block/elevator.c:562
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff8141f1c0-ffffffff8141f1e8: elv_bio_merged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elv_bio_merged(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449ca0)
Location: block/elevator.c:579
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff81449ca0-ffffffff81449cca: elv_bio_merged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elv_bio_merged(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147ca00)
Location: block/elevator.c:548
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff8147ca00-ffffffff8147ca2a: elv_bio_merged (STB_GLOBAL)
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
</ul>
