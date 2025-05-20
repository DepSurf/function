# Function: <code>wbt_track</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814190e1)
Location: block/blk-wbt.h:43
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff81424651)
Location: block/blk-wbt.h:43
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81426ff8)
Location: block/blk-wbt.h:43
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff814313c0)
Location: block/blk-wbt.h:43
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81452018)
Location: block/blk-wbt.h:44
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8145cdae)
Location: block/blk-wbt.h:44
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8148525e)
Location: block/blk-wbt.h:91
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff81490682)
Location: block/blk-wbt.h:91
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd2c0)
Location: block/blk-wbt.c:594
Inline: False
```
**Symbols:**

```
ffffffff814cd2c0-ffffffff814cd2ef: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fbb50)
Location: block/blk-wbt.c:595
Inline: False
```
**Symbols:**

```
ffffffff814fbb50-ffffffff814fbb7f: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81519980)
Location: block/blk-wbt.c:597
Inline: False
```
**Symbols:**

```
ffffffff81519980-ffffffff815199af: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81579f90)
Location: block/blk-wbt.c:589
Inline: False
```
**Symbols:**

```
ffffffff81579f90-ffffffff8157a01d: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81596ea0)
Location: block/blk-wbt.c:589
Inline: False
```
**Symbols:**

```
ffffffff81596ea0-ffffffff81596f2d: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159dbc0)
Location: block/blk-wbt.c:590
Inline: False
```
**Symbols:**

```
ffffffff8159dbc0-ffffffff8159dbe6: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816062a0)
Location: block/blk-wbt.c:592
Inline: False
```
**Symbols:**

```
ffffffff816062a0-ffffffff816062c6: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816b9f70)
Location: block/blk-wbt.c:592
Inline: False
```
**Symbols:**

```
ffffffff816b9f70-ffffffff816b9f9f: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177a490)
Location: block/blk-wbt.c:606
Inline: False
```
**Symbols:**

```
ffffffff8177a490-ffffffff8177a4bf: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba280)
Location: block/blk-wbt.c:665
Inline: False
```
**Symbols:**

```
ffffffff817ba280-ffffffff817ba2af: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817fe9f0)
Location: block/blk-wbt.c:664
Inline: False
```
**Symbols:**

```
ffffffff817fe9f0-ffffffff817fea1f: wbt_track (STB_LOCAL)
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
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff800010620f30)
Location: block/blk-wbt.c:597
Inline: False
```
**Symbols:**

```
ffff800010620f30-ffff800010620f90: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c8fd0)
Location: block/blk-wbt.c:597
Inline: False
```
**Symbols:**

```
c07c8fd0-c07c9024: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c13e0)
Location: block/blk-wbt.c:597
Inline: False
```
**Symbols:**

```
c0000000007c13e0-c0000000007c1448: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe0004539e6)
Location: block/blk-wbt.c:597
Inline: False
```
**Symbols:**

```
ffffffe0004539e6-ffffffe000453a3c: wbt_track (STB_LOCAL)
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
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81511f60)
Location: block/blk-wbt.c:597
Inline: False
```
**Symbols:**

```
ffffffff81511f60-ffffffff81511f8f: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81502280)
Location: block/blk-wbt.c:597
Inline: False
```
**Symbols:**

```
ffffffff81502280-ffffffff815022af: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150dff0)
Location: block/blk-wbt.c:597
Inline: False
```
**Symbols:**

```
ffffffff8150dff0-ffffffff8150e01f: wbt_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wbt_track(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81527610)
Location: block/blk-wbt.c:597
Inline: False
```
**Symbols:**

```
ffffffff81527610-ffffffff8152763f: wbt_track (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
