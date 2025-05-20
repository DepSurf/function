# Function: <code>mq_flush_data_end_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff813bd7a0)
Location: block/blk-flush.c:352
Inline: False
```
**Symbols:**

```
ffffffff813bd7a0-ffffffff813bd84e: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814016f0)
Location: block/blk-flush.c:353
Inline: False
```
**Symbols:**

```
ffffffff814016f0-ffffffff8140179e: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8141b340)
Location: block/blk-flush.c:379
Inline: False
```
**Symbols:**

```
ffffffff8141b340-ffffffff8141b3ff: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81429430)
Location: block/blk-flush.c:387
Inline: False
```
**Symbols:**

```
ffffffff81429430-ffffffff814294d5: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814547d0)
Location: block/blk-flush.c:399
Inline: False
```
**Symbols:**

```
ffffffff814547d0-ffffffff814548c8: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81487c10)
Location: block/blk-flush.c:404
Inline: False
```
**Symbols:**

```
ffffffff81487c10-ffffffff81487d07: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814a1a80)
Location: block/blk-flush.c:317
Inline: False
```
**Symbols:**

```
ffffffff814a1a80-ffffffff814a1b54: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-flush.c (0)
Location: block/blk-flush.c:316
Inline: False
```
**Symbols:**

```
ffffffff814cfbd0-ffffffff814cfc9c: mq_flush_data_end_io (STB_LOCAL)
ffffffff814d00b9-ffffffff814d00da: mq_flush_data_end_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e8f30)
Location: block/blk-flush.c:327
Inline: False
```
**Symbols:**

```
ffffffff814e8f30-ffffffff814e8ffa: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81547e60)
Location: block/blk-flush.c:336
Inline: False
```
**Symbols:**

```
ffffffff81547e60-ffffffff81547f26: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81563b80)
Location: block/blk-flush.c:337
Inline: False
```
**Symbols:**

```
ffffffff81563b80-ffffffff81563c65: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8156c300)
Location: block/blk-flush.c:336
Inline: False
```
**Symbols:**

```
ffffffff8156c300-ffffffff8156c3e5: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff815d07a0)
Location: block/blk-flush.c:351
Inline: False
```
**Symbols:**

```
ffffffff815d07a0-ffffffff815d0885: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8167bfa0)
Location: block/blk-flush.c:357
Inline: False
```
**Symbols:**

```
ffffffff8167bfa0-ffffffff8167c0c0: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum rq_end_io_ret mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81738820)
Location: block/blk-flush.c:358
Inline: False
```
**Symbols:**

```
ffffffff81738820-ffffffff81738922: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum rq_end_io_ret mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81774e60)
Location: block/blk-flush.c:358
Inline: False
```
**Symbols:**

```
ffffffff81774e60-ffffffff81774f62: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum rq_end_io_ret mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817b7170)
Location: block/blk-flush.c:351
Inline: False
```
**Symbols:**

```
ffffffff817b7170-ffffffff817b729a: mq_flush_data_end_io (STB_LOCAL)
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
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffff8000105e6ea0)
Location: block/blk-flush.c:327
Inline: False
```
**Symbols:**

```
ffff8000105e6ea0-ffff8000105e7000: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c0793bb8)
Location: block/blk-flush.c:327
Inline: False
```
**Symbols:**

```
c0793bb8-c0793cb4: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c00000000077ba50)
Location: block/blk-flush.c:327
Inline: False
```
**Symbols:**

```
c00000000077ba50-c00000000077bb7c: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffe000428016)
Location: block/blk-flush.c:327
Inline: False
```
**Symbols:**

```
ffffffe000428016-ffffffe0004280d2: mq_flush_data_end_io (STB_LOCAL)
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
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e1510)
Location: block/blk-flush.c:327
Inline: False
```
**Symbols:**

```
ffffffff814e1510-ffffffff814e15da: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814d1ea0)
Location: block/blk-flush.c:327
Inline: False
```
**Symbols:**

```
ffffffff814d1ea0-ffffffff814d1f6a: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814dd5a0)
Location: block/blk-flush.c:327
Inline: False
```
**Symbols:**

```
ffffffff814dd5a0-ffffffff814dd66a: mq_flush_data_end_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mq_flush_data_end_io(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814f6400)
Location: block/blk-flush.c:327
Inline: False
```
**Symbols:**

```
ffffffff814f6400-ffffffff814f64ca: mq_flush_data_end_io (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>enum rq_end_io_ret</code>
</li>
</ul>
</details>
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
