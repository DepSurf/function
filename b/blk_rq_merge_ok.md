# Function: <code>blk_rq_merge_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813c1b20)
Location: block/blk-merge.c:750
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_mq_attempt_merge
```
**Symbols:**

```
ffffffff813c1b20-ffffffff813c1c69: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81405b40)
Location: block/blk-merge.c:782
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81405b40-ffffffff81405c02: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141fde0)
Location: block/blk-merge.c:773
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8141fde0-ffffffff8141fead: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142dd30)
Location: block/blk-merge.c:776
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff8142dd30-ffffffff8142de41: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81458f60)
Location: block/blk-merge.c:777
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:__blk_mq_sched_bio_merge
```
**Symbols:**

```
ffffffff81458f60-ffffffff81459066: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148c4c0)
Location: block/blk-merge.c:808
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff8148c4c0-ffffffff8148c5b9: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a6090)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814a6090-ffffffff814a617b: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d3f70)
Location: block/blk-merge.c:795
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814d3f70-ffffffff814d406a: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814ed2a0)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814ed2a0-ffffffff814ed39a: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154ce20)
Location: block/blk-merge.c:845
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff8154ce20-ffffffff8154cf29: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81569340)
Location: block/blk-merge.c:864
Inline: True
Direct callers:
  - block/blk-merge.c:blk_bio_list_merge
  - block/blk-merge.c:blk_attempt_plug_merge
```
**Symbols:**

```
ffffffff81569340-ffffffff81569449: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815712a0)
Location: block/blk-merge.c:867
Inline: True
Direct callers:
  - block/blk-merge.c:blk_bio_list_merge
  - block/blk-merge.c:blk_attempt_plug_merge
```
**Symbols:**

```
ffffffff815712a0-ffffffff815713b3: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d5960)
Location: block/blk-merge.c:850
Inline: True
Direct callers:
  - block/blk-merge.c:blk_bio_list_merge
  - block/blk-merge.c:blk_attempt_plug_merge
```
**Symbols:**

```
ffffffff815d5960-ffffffff815d5a72: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81681710)
Location: block/blk-merge.c:859
Inline: False
Direct callers:
  - block/elevator.c:elv_bio_merge_ok
  - block/blk-merge.c:blk_bio_list_merge
  - block/blk-merge.c:blk_attempt_plug_merge
```
**Symbols:**

```
ffffffff81681710-ffffffff816817d0: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173ece0)
Location: block/blk-merge.c:924
Inline: False
Direct callers:
  - block/elevator.c:elv_bio_merge_ok
  - block/blk-merge.c:blk_bio_list_merge
  - block/blk-merge.c:blk_attempt_plug_merge
```
**Symbols:**

```
ffffffff8173ece0-ffffffff8173eda0: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177b250)
Location: block/blk-merge.c:920
Inline: False
Direct callers:
  - block/elevator.c:elv_bio_merge_ok
  - block/blk-merge.c:blk_bio_list_merge
  - block/blk-merge.c:blk_attempt_plug_merge
```
**Symbols:**

```
ffffffff8177b250-ffffffff8177b310: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bd640)
Location: block/blk-merge.c:916
Inline: False
Direct callers:
  - block/elevator.c:elv_bio_merge_ok
  - block/blk-merge.c:blk_bio_list_merge
  - block/blk-merge.c:blk_attempt_plug_merge
```
**Symbols:**

```
ffffffff817bd640-ffffffff817bd700: blk_rq_merge_ok (STB_GLOBAL)
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
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105ebd08)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffff8000105ebd08-ffff8000105ebe4c: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0798210)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
c0798210-c079835c: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0000000007811c0)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
c0000000007811c0-c000000000781370: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042ba72)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffe00042ba72-ffffffe00042bb6e: blk_rq_merge_ok (STB_GLOBAL)
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
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e5880)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814e5880-ffffffff814e597a: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d5e30)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814d5e30-ffffffff814d5f2a: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e1910)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814e1910-ffffffff814e1a0a: blk_rq_merge_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_rq_merge_ok(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814fa7d0)
Location: block/blk-merge.c:848
Inline: False
Direct callers:
  - block/blk-core.c:blk_attempt_plug_merge
  - block/blk-mq-sched.c:blk_mq_bio_list_merge
```
**Symbols:**

```
ffffffff814fa7d0-ffffffff814fa8ca: blk_rq_merge_ok (STB_GLOBAL)
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
