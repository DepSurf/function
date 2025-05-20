# Function: <code>blk_mq_make_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c62c0)
Location: block/blk-mq.c:1238
Inline: False
```
**Symbols:**

```
ffffffff813c62c0-ffffffff813c66c4: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8140a2b0)
Location: block/blk-mq.c:1305
Inline: False
```
**Symbols:**

```
ffffffff8140a2b0-ffffffff8140a81f: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81424de0)
Location: block/blk-mq.c:1343
Inline: False
```
**Symbols:**

```
ffffffff81424de0-ffffffff814252b1: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814312b0)
Location: block/blk-mq.c:1554
Inline: False
```
**Symbols:**

```
ffffffff814312b0-ffffffff81431873: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145cca0)
Location: block/blk-mq.c:1691
Inline: False
```
**Symbols:**

```
ffffffff8145cca0-ffffffff8145d20d: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81490540)
Location: block/blk-mq.c:1753
Inline: False
```
**Symbols:**

```
ffffffff81490540-ffffffff814909f5: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aa960)
Location: block/blk-mq.c:1922
Inline: False
```
**Symbols:**

```
ffffffff814aa960-ffffffff814aae31: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8410)
Location: block/blk-mq.c:1931
Inline: False
```
**Symbols:**

```
ffffffff814d8410-ffffffff814d89a6: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f17c0)
Location: block/blk-mq.c:1951
Inline: False
```
**Symbols:**

```
ffffffff814f17c0-ffffffff814f1d63: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550eb0)
Location: block/blk-mq.c:2033
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff81550eb0-ffffffff81551497: blk_mq_make_request (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f0e60)
Location: block/blk-mq.c:1951
Inline: False
```
**Symbols:**

```
ffff8000105f0e60-ffff8000105f1464: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079cecc)
Location: block/blk-mq.c:1951
Inline: False
```
**Symbols:**

```
c079cecc-c079d580: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000787af0)
Location: block/blk-mq.c:1951
Inline: False
```
**Symbols:**

```
c000000000787af0-c000000000788250: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042fb42)
Location: block/blk-mq.c:1951
Inline: False
```
**Symbols:**

```
ffffffe00042fb42-ffffffe00043007a: blk_mq_make_request (STB_LOCAL)
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
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9da0)
Location: block/blk-mq.c:1951
Inline: False
```
**Symbols:**

```
ffffffff814e9da0-ffffffff814ea343: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814da300)
Location: block/blk-mq.c:1951
Inline: False
```
**Symbols:**

```
ffffffff814da300-ffffffff814da8a3: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5e30)
Location: block/blk-mq.c:1951
Inline: False
```
**Symbols:**

```
ffffffff814e5e30-ffffffff814e63d3: blk_mq_make_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_qc_t blk_mq_make_request(struct request_queue *q, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814feda0)
Location: block/blk-mq.c:1951
Inline: False
```
**Symbols:**

```
ffffffff814feda0-ffffffff814ff3b1: blk_mq_make_request (STB_LOCAL)
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
