# Function: <code>__bio_queue_enter</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __bio_queue_enter(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff816788b0)
Location: block/blk-core.c:362
Inline: False
Direct callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
```
**Symbols:**

```
ffffffff816788b0-ffffffff81678afd: __bio_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __bio_queue_enter(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81734d10)
Location: block/blk-core.c:340
Inline: False
Direct callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
```
**Symbols:**

```
ffffffff81734d10-ffffffff81734f7a: __bio_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __bio_queue_enter(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81771270)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio
  - block/blk-mq.c:blk_mq_get_new_requests
```
**Symbols:**

```
ffffffff81771270-ffffffff817714d9: __bio_queue_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __bio_queue_enter(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b35b0)
Location: block/blk-core.c:339
Inline: False
Direct callers:
  - block/blk-core.c:__submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff817b35b0-ffffffff817b3819: __bio_queue_enter (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
