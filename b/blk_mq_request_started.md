# Function: <code>blk_mq_request_started</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c2ca0)
Location: block/blk-mq.c:390
Inline: False
```
**Symbols:**

```
ffffffff813c2ca0-ffffffff813c2cb5: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814068a0)
Location: block/blk-mq.c:446
Inline: False
```
**Symbols:**

```
ffffffff814068a0-ffffffff814068b5: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81420d10)
Location: block/blk-mq.c:460
Inline: False
```
**Symbols:**

```
ffffffff81420d10-ffffffff81420d25: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142ec90)
Location: block/blk-mq.c:539
Inline: False
```
**Symbols:**

```
ffffffff8142ec90-ffffffff8142eca5: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145a120)
Location: block/blk-mq.c:581
Inline: False
```
**Symbols:**

```
ffffffff8145a120-ffffffff8145a135: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148d7a0)
Location: block/blk-mq.c:624
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffffffff8148d7a0-ffffffff8148d7b9: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7030)
Location: block/blk-mq.c:660
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffffffff814a7030-ffffffff814a7049: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d4f80)
Location: block/blk-mq.c:662
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffffffff814d4f80-ffffffff814d4f99: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee240)
Location: block/blk-mq.c:666
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffffffff814ee240-ffffffff814ee259: blk_mq_request_started (STB_GLOBAL)
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
In block/blk-mq.c (ffffffff8154deb5)
Location: include/linux/blk-mq.h:489
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
```
```
In block/blk-mq-tag.c (ffffffff815547d1)
Location: include/linux/blk-mq.h:489
Inline: True
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
In block/blk-mq.c (ffffffff8156a355)
Location: include/linux/blk-mq.h:487
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
```
```
In block/blk-mq-tag.c (ffffffff81570eb1)
Location: include/linux/blk-mq.h:487
Inline: True
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
In block/blk-mq.c (ffffffff81572295)
Location: include/linux/blk-mq.h:492
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
```
```
In block/blk-mq-tag.c (ffffffff81578f71)
Location: include/linux/blk-mq.h:492
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_tags_iter
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
In block/blk-mq.c (ffffffff815d6955)
Location: include/linux/blk-mq.h:502
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
```
```
In block/blk-mq-tag.c (ffffffff815de1a1)
Location: include/linux/blk-mq.h:502
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_tags_iter
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
In block/blk-mq.c (ffffffff816825c5)
Location: include/linux/blk-mq.h:779
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
```
```
In block/blk-mq-tag.c (ffffffff8168c1af)
Location: include/linux/blk-mq.h:779
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_tags_iter
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
In block/blk-mq.c (ffffffff8173fc85)
Location: include/linux/blk-mq.h:799
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
```
```
In block/blk-mq-tag.c (ffffffff8174a930)
Location: include/linux/blk-mq.h:799
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_tags_iter
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
In block/blk-mq.c (ffffffff8177c1e5)
Location: include/linux/blk-mq.h:795
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
```
```
In block/blk-mq-tag.c (ffffffff81787010)
Location: include/linux/blk-mq.h:795
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_tags_iter
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
In block/blk-mq.c (ffffffff817bebf5)
Location: include/linux/blk-mq.h:786
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
```
```
In block/blk-mq-tag.c (ffffffff817c96f0)
Location: include/linux/blk-mq.h:786
Inline: True
Inline callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ecde8)
Location: block/blk-mq.c:666
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffff8000105ecde8-ffff8000105ece18: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0799348)
Location: block/blk-mq.c:666
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
c0799348-c079936c: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000782900)
Location: block/blk-mq.c:666
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
c000000000782900-c000000000782918: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042c8b4)
Location: block/blk-mq.c:666
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffffffe00042c8b4-ffffffe00042c8de: blk_mq_request_started (STB_GLOBAL)
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
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6820)
Location: block/blk-mq.c:666
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffffffff814e6820-ffffffff814e6839: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6d90)
Location: block/blk-mq.c:666
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffffffff814d6d90-ffffffff814d6da9: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e28b0)
Location: block/blk-mq.c:666
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffffffff814e28b0-ffffffff814e28c9: blk_mq_request_started (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_request_started(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fb730)
Location: block/blk-mq.c:666
Inline: True
Direct callers:
  - block/blk-mq-tag.c:bt_tags_iter
```
**Symbols:**

```
ffffffff814fb730-ffffffff814fb749: blk_mq_request_started (STB_GLOBAL)
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
