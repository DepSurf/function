# Function: <code>blk_mq_add_to_requeue_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c3710)
Location: block/blk-mq.c:491
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_queue_rq
```
**Symbols:**

```
ffffffff813c3710-ffffffff813c37a9: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81407430)
Location: block/blk-mq.c:547
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_queue_rq
```
**Symbols:**

```
ffffffff81407430-ffffffff814074c9: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814219b0)
Location: block/blk-mq.c:564
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_queue_rq
```
**Symbols:**

```
ffffffff814219b0-ffffffff81421a65: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814300c0)
Location: block/blk-mq.c:651
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_queue_rq
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814300c0-ffffffff8143016d: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b980)
Location: block/blk-mq.c:706
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_queue_rq
```
**Symbols:**

```
ffffffff8145b980-ffffffff8145ba2d: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e480)
Location: block/blk-mq.c:721
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_queue_rq
```
**Symbols:**

```
ffffffff8148e480-ffffffff8148e550: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7e10)
Location: block/blk-mq.c:765
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff814a7e10-ffffffff814a7ee0: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7750)
Location: block/blk-mq.c:765
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff814d7750-ffffffff814d781d: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0ad0)
Location: block/blk-mq.c:778
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff814f0ad0-ffffffff814f0b9d: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551cd0)
Location: block/blk-mq.c:777
Inline: False
Direct callers:
  - block/blk-flush.c:blk_kick_flush
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff81551cd0-ffffffff81551d9d: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156de00)
Location: block/blk-mq.c:827
Inline: False
Direct callers:
  - block/blk-flush.c:blk_kick_flush
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff8156de00-ffffffff8156decd: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815758e0)
Location: block/blk-mq.c:801
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff815758e0-ffffffff815759ad: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d9e00)
Location: block/blk-mq.c:807
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_requeue_request
```
**Symbols:**

```
ffffffff815d9e00-ffffffff815d9ecd: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81687840)
Location: block/blk-mq.c:1357
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_requeue_request
```
**Symbols:**

```
ffffffff81687840-ffffffff81687929: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745bb0)
Location: block/blk-mq.c:1485
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_requeue_request
```
**Symbols:**

```
ffffffff81745bb0-ffffffff81745c99: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105efec8)
Location: block/blk-mq.c:778
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffff8000105efec8-ffff8000105efff0: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079c0ac)
Location: block/blk-mq.c:778
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
c079c0ac-c079c160: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000786630)
Location: block/blk-mq.c:778
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_requeue_request
```
**Symbols:**

```
c000000000786630-c000000000786760: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042ef14)
Location: block/blk-mq.c:778
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffe00042ef14-ffffffe00042efc2: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e90b0)
Location: block/blk-mq.c:778
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff814e90b0-ffffffff814e917d: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9620)
Location: block/blk-mq.c:778
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff814d9620-ffffffff814d96ed: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5140)
Location: block/blk-mq.c:778
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff814e5140-ffffffff814e520d: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_add_to_requeue_list(struct request *rq, bool at_head, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fe0a0)
Location: block/blk-mq.c:778
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff814fe0a0-ffffffff814fe16d: blk_mq_add_to_requeue_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool kick_requeue_list</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
