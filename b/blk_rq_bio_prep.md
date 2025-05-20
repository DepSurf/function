# Function: <code>blk_rq_bio_prep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_rq_bio_prep(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bb440)
Location: block/blk-core.c:2967
Inline: False
Direct callers:
  - block/blk-core.c:init_request_from_bio
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff813bb440-ffffffff813bb4bc: blk_rq_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_rq_bio_prep(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ff230)
Location: block/blk-core.c:2939
Inline: False
Direct callers:
  - block/blk-core.c:init_request_from_bio
```
**Symbols:**

```
ffffffff813ff230-ffffffff813ff2cf: blk_rq_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_rq_bio_prep(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418c70)
Location: block/blk-core.c:2936
Inline: False
Direct callers:
  - block/blk-core.c:init_request_from_bio
```
**Symbols:**

```
ffffffff81418c70-ffffffff81418cea: blk_rq_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_rq_bio_prep(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81426b50)
Location: block/blk-core.c:3034
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_request_from_bio
  - block/blk-map.c:blk_rq_append_bio
```
**Symbols:**

```
ffffffff81426b50-ffffffff81426bc3: blk_rq_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_rq_bio_prep(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81451b70)
Location: block/blk-core.c:3258
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_request_from_bio
```
**Symbols:**

```
ffffffff81451b70-ffffffff81451bdc: blk_rq_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_rq_bio_prep(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484dc0)
Location: block/blk-core.c:3403
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_request_from_bio
```
**Symbols:**

```
ffffffff81484dc0-ffffffff81484e3d: blk_rq_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_rq_bio_prep(struct request_queue *q, struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149fca0)
Location: block/blk-core.c:1510
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_request_from_bio
```
**Symbols:**

```
ffffffff8149fca0-ffffffff8149fd1d: blk_rq_bio_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814d16fb)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff814d85a6)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814eaaab)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff814f1956)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81549dcd)
Location: block/blk.h:101
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff81551060)
Location: block/blk.h:101
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156584e)
Location: include/linux/blk-mq.h:597
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff8156ef19)
Location: include/linux/blk-mq.h:597
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156de82)
Location: include/linux/blk-mq.h:614
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff81576af2)
Location: include/linux/blk-mq.h:614
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff815d2472)
Location: include/linux/blk-mq.h:624
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff815db7a2)
Location: include/linux/blk-mq.h:624
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8167e18f)
Location: include/linux/blk-mq.h:931
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff8168993f)
Location: include/linux/blk-mq.h:931
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8173c4d4)
Location: include/linux/blk-mq.h:959
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff81747e2d)
Location: include/linux/blk-mq.h:959
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81778a83)
Location: include/linux/blk-mq.h:959
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff81784463)
Location: include/linux/blk-mq.h:959
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817bae44)
Location: include/linux/blk-mq.h:956
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff817c6759)
Location: include/linux/blk-mq.h:956
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffff8000105e942c)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffff8000105f100c)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (c07958e4)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (c079d0ac)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (c00000000077dfd0)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (c000000000787d04)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffe000429ae4)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffe00042fcb8)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814e308b)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff814e9f36)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814d3a0b)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff814da496)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814df11b)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff814e5fc6)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff814f7f8b)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff814fef36)
Location: block/blk.h:110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
</ul>
