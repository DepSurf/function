# Function: <code>elv_merged_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3e30)
Location: block/elevator.c:497
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff813b3e30-ffffffff813b3e80: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7b10)
Location: block/elevator.c:496
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff813f7b10-ffffffff813f7b60: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411540)
Location: block/elevator.c:494
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff81411540-ffffffff81411590: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141f0a0)
Location: block/elevator.c:522
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8141f0a0-ffffffff8141f10a: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449b80)
Location: block/elevator.c:539
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81449b80-ffffffff81449bed: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c8d0)
Location: block/elevator.c:508
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8147c8d0-ffffffff8147c941: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a890)
Location: block/elevator.c:379
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8149a890-ffffffff8149a8e3: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8960)
Location: block/elevator.c:380
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814c8960-ffffffff814c89b3: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1a80)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814e1a80-ffffffff814e1ad1: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815405f0)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff815405f0-ffffffff81540673: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155cd90)
Location: block/elevator.c:389
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8155cd90-ffffffff8155ce13: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81565620)
Location: block/elevator.c:389
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81565620-ffffffff815656a3: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9a10)
Location: block/elevator.c:397
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff815c9a10-ffffffff815c9a93: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674d10)
Location: block/elevator.c:402
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81674d10-ffffffff81674db7: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730a80)
Location: block/elevator.c:370
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81730a80-ffffffff81730b27: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176cce0)
Location: block/elevator.c:370
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8176cce0-ffffffff8176cd87: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817aef10)
Location: block/elevator.c:370
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff817aef10-ffffffff817aefb9: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105debc8)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffff8000105debc8-ffff8000105dec48: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078bb38)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c078bb38-c078bb94: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770a40)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c000000000770a40-c000000000770af4: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000421736)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffe000421736-ffffffe00042179a: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814da060)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814da060-ffffffff814da0b1: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814caa10)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814caa10-ffffffff814caa61: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d60f0)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814d60f0-ffffffff814d6141: elv_merged_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void elv_merged_request(struct request_queue *q, struct request *rq, enum elv_merge type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814eecf0)
Location: block/elevator.c:390
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814eecf0-ffffffff814eed41: elv_merged_request (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int type</code> ➡️ <code>enum elv_merge type</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
