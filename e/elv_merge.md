# Function: <code>elv_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3d60)
Location: block/elevator.c:411
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff813b3d60-ffffffff813b3e29: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7a40)
Location: block/elevator.c:410
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff813f7a40-ffffffff813f7b08: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411470)
Location: block/elevator.c:408
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff81411470-ffffffff81411537: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141ef20)
Location: block/elevator.c:434
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8141ef20-ffffffff8141eff9: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449a00)
Location: block/elevator.c:451
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81449a00-ffffffff81449adb: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c740)
Location: block/elevator.c:420
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8147c740-ffffffff8147c821: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a730)
Location: block/elevator.c:293
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8149a730-ffffffff8149a7f7: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c87f0)
Location: block/elevator.c:294
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814c87f0-ffffffff814c88b7: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1910)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814e1910-ffffffff814e19d4: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81540480)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81540480-ffffffff81540544: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155cc20)
Location: block/elevator.c:303
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8155cc20-ffffffff8155cce4: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815654c0)
Location: block/elevator.c:303
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff815654c0-ffffffff8156557d: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9850)
Location: block/elevator.c:303
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff815c9850-ffffffff815c992c: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674b20)
Location: block/elevator.c:308
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81674b20-ffffffff81674c0a: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730870)
Location: block/elevator.c:276
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81730870-ffffffff8173095a: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176cad0)
Location: block/elevator.c:276
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8176cad0-ffffffff8176cbc0: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817aed00)
Location: block/elevator.c:276
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff817aed00-ffffffff817aeded: elv_merge (STB_GLOBAL)
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
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105dea18)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffff8000105dea18-ffff8000105deb10: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b9b4)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c078b9b4-c078ba90: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770780)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c000000000770780-c00000000077092c: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe0004215f2)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffe0004215f2-ffffffe0004216aa: elv_merge (STB_GLOBAL)
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
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9ef0)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814d9ef0-ffffffff814d9fb4: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca8a0)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814ca8a0-ffffffff814ca964: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5f80)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814d5f80-ffffffff814d6044: elv_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum elv_merge elv_merge(struct request_queue *q, struct request **req, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814eeb80)
Location: block/elevator.c:304
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814eeb80-ffffffff814eec44: elv_merge (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum elv_merge</code>
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
