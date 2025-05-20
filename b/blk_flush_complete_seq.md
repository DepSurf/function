# Function: <code>blk_flush_complete_seq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff813bd470)
Location: block/blk-flush.c:166
Inline: False
Direct callers:
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_insert_flush
```
**Symbols:**

```
ffffffff813bd470-ffffffff813bd726: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814013a0)
Location: block/blk-flush.c:167
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff814013a0-ffffffff81401677: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8141afe0)
Location: block/blk-flush.c:164
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff8141afe0-ffffffff8141b2ae: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81429010)
Location: block/blk-flush.c:165
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff81429010-ffffffff81429307: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81454100)
Location: block/blk-flush.c:165
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff81454100-ffffffff81454410: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81487540)
Location: block/blk-flush.c:165
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff81487540-ffffffff81487860: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814a16f0)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff814a16f0-ffffffff814a19b9: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814cf830)
Location: block/blk-flush.c:155
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff814cf830-ffffffff814cfaf9: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e8b90)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff814e8b90-ffffffff814e8e59: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81547c30)
Location: block/blk-flush.c:164
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff81547c30-ffffffff81547dd6: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81563950)
Location: block/blk-flush.c:163
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff81563950-ffffffff81563af6: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8156bfb0)
Location: block/blk-flush.c:163
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff8156bfb0-ffffffff8156c253: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-flush.c (0)
Location: block/blk-flush.c:163
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff815d04d0-ffffffff815d0791: blk_flush_complete_seq (STB_LOCAL)
ffffffff81cd8109-ffffffff81cd8130: blk_flush_complete_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-flush.c (0)
Location: block/blk-flush.c:170
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff8167bcc0-ffffffff8167bf9a: blk_flush_complete_seq (STB_LOCAL)
ffffffff81e8b4cf-ffffffff81e8b4f6: blk_flush_complete_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-flush.c (0)
Location: block/blk-flush.c:170
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff81738540-ffffffff81738801: blk_flush_complete_seq (STB_LOCAL)
ffffffff82075cd7-ffffffff82075cfe: blk_flush_complete_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-flush.c (0)
Location: block/blk-flush.c:163
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff81774b10-ffffffff81774e42: blk_flush_complete_seq (STB_LOCAL)
ffffffff820f5b54-ffffffff820f5b7b: blk_flush_complete_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-flush.c (0)
Location: block/blk-flush.c:163
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff817b6e90-ffffffff817b715b: blk_flush_complete_seq (STB_LOCAL)
ffffffff821d2fa0-ffffffff821d2fc7: blk_flush_complete_seq.cold (STB_LOCAL)
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
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffff8000105e6b30)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffff8000105e6b30-ffff8000105e6dcc: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c0793874)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
c0793874-c0793af8: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c00000000077b370)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
c00000000077b370-c00000000077b690: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffe000427c6e)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffe000427c6e-ffffffe000427e8e: blk_flush_complete_seq (STB_LOCAL)
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
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e1170)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff814e1170-ffffffff814e1439: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814d1b00)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff814d1b00-ffffffff814d1dc9: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814dd200)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff814dd200-ffffffff814dd4c9: blk_flush_complete_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_flush_complete_seq(struct request *rq, struct blk_flush_queue *fq, unsigned int seq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814f6060)
Location: block/blk-flush.c:156
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff814f6060-ffffffff814f6329: blk_flush_complete_seq (STB_LOCAL)
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
<code>int error</code> ➡️ <code>blk_status_t error</code>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
