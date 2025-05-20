# Function: <code>blk_bio_list_merge</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81569450)
Location: block/blk-merge.c:1095
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff81569450-ffffffff815694e2: blk_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815713c0)
Location: block/blk-merge.c:1098
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff815713c0-ffffffff81571452: blk_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d5a80)
Location: block/blk-merge.c:1081
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff815d5a80-ffffffff815d5b12: blk_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff816817d0)
Location: block/blk-merge.c:1070
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff816817d0-ffffffff81681872: blk_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173edb0)
Location: block/blk-merge.c:1139
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff8173edb0-ffffffff8173ee52: blk_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177b320)
Location: block/blk-merge.c:1135
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff8177b320-ffffffff8177b3c2: blk_bio_list_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_bio_list_merge(struct request_queue *q, struct list_head *list, struct bio *bio, unsigned int nr_segs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bd710)
Location: block/blk-merge.c:1131
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff817bd710-ffffffff817bd7b2: blk_bio_list_merge (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
