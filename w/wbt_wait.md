# Function: <code>wbt_wait</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
enum wbt_flags wbt_wait(struct rq_wb *rwb, struct bio *bio, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8144a880)
Location: block/blk-wbt.c:599
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8144a880-ffffffff8144abf9: wbt_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum wbt_flags wbt_wait(struct rq_wb *rwb, struct bio *bio, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81458b30)
Location: block/blk-wbt.c:586
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81458b30-ffffffff81458e80: wbt_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum wbt_flags wbt_wait(struct rq_wb *rwb, struct bio *bio, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81484890)
Location: block/blk-wbt.c:585
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81484890-ffffffff81484bdb: wbt_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum wbt_flags wbt_wait(struct rq_wb *rwb, struct bio *bio, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b9690)
Location: block/blk-wbt.c:617
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814b9690-ffffffff814b9a95: wbt_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd3a0)
Location: block/blk-wbt.c:576
Inline: False
```
**Symbols:**

```
ffffffff814cd3a0-ffffffff814cd47b: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fbc30)
Location: block/blk-wbt.c:577
Inline: False
```
**Symbols:**

```
ffffffff814fbc30-ffffffff814fbd16: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815199f0)
Location: block/blk-wbt.c:579
Inline: False
```
**Symbols:**

```
ffffffff815199f0-ffffffff81519ad6: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8157a080)
Location: block/blk-wbt.c:571
Inline: False
```
**Symbols:**

```
ffffffff8157a080-ffffffff8157a198: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81596f90)
Location: block/blk-wbt.c:571
Inline: False
```
**Symbols:**

```
ffffffff81596f90-ffffffff815970a8: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159dbf0)
Location: block/blk-wbt.c:572
Inline: False
```
**Symbols:**

```
ffffffff8159dbf0-ffffffff8159dccf: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816062d0)
Location: block/blk-wbt.c:574
Inline: False
```
**Symbols:**

```
ffffffff816062d0-ffffffff816063af: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816b9fa0)
Location: block/blk-wbt.c:574
Inline: False
```
**Symbols:**

```
ffffffff816b9fa0-ffffffff816ba0a3: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177a4d0)
Location: block/blk-wbt.c:588
Inline: False
```
**Symbols:**

```
ffffffff8177a4d0-ffffffff8177a5d2: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba2c0)
Location: block/blk-wbt.c:647
Inline: False
```
**Symbols:**

```
ffffffff817ba2c0-ffffffff817ba3bd: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817fea30)
Location: block/blk-wbt.c:646
Inline: False
```
**Symbols:**

```
ffffffff817fea30-ffffffff817feb2d: wbt_wait (STB_LOCAL)
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
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff8000106212e0)
Location: block/blk-wbt.c:579
Inline: False
```
**Symbols:**

```
ffff8000106212e0-ffff8000106213d0: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c91cc)
Location: block/blk-wbt.c:579
Inline: False
```
**Symbols:**

```
c07c91cc-c07c92cc: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c14c0)
Location: block/blk-wbt.c:579
Inline: False
```
**Symbols:**

```
c0000000007c14c0-c0000000007c1644: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe000453be6)
Location: block/blk-wbt.c:579
Inline: False
```
**Symbols:**

```
ffffffe000453be6-ffffffe000453ca6: wbt_wait (STB_LOCAL)
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
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81511fd0)
Location: block/blk-wbt.c:579
Inline: False
```
**Symbols:**

```
ffffffff81511fd0-ffffffff815120b6: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815022f0)
Location: block/blk-wbt.c:579
Inline: False
```
**Symbols:**

```
ffffffff815022f0-ffffffff815023d6: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150e060)
Location: block/blk-wbt.c:579
Inline: False
```
**Symbols:**

```
ffffffff8150e060-ffffffff8150e146: wbt_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wbt_wait(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81527680)
Location: block/blk-wbt.c:579
Inline: False
```
**Symbols:**

```
ffffffff81527680-ffffffff81527766: wbt_wait (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_qos *rqos</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_wb *rwb</code>
</li>
<li>
<b>Param removed. </b>
<code>spinlock_t *lock</code>
</li>
<li>
<b>Return type changed. </b>
<code>enum wbt_flags</code> ➡️ <code>void</code>
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
