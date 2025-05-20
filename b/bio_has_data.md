# Function: <code>bio_has_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b6816)
Location: include/linux/bio.h:105
Inline: True
Inline callers:
  - block/blk-core.c:blk_dump_rq_flags
  - block/blk-core.c:submit_bio
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_rq_bio_prep
```
```
In block/blk-merge.c (ffffffff813c0bc8)
Location: include/linux/bio.h:105
Inline: True
Inline callers:
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:blk_rq_merge_ok
  - block/blk-merge.c:blk_rq_merge_ok
```
```
In block/bounce.c (ffffffff813d4f1c)
Location: include/linux/bio.h:105
Inline: True
```
```
In block/bio-integrity.c (ffffffff813e6f35)
Location: include/linux/bio.h:105
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_enabled
```
```
In drivers/md/dm.c (ffffffff816a2ae5)
Location: include/linux/bio.h:105
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ff263)
Location: include/linux/bio.h:70
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_bio_prep
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:blk_dump_rq_flags
```
```
In block/blk-merge.c (ffffffff81405066)
Location: include/linux/bio.h:70
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:bio_data
```
```
In block/bounce.c (ffffffff8141abbb)
Location: include/linux/bio.h:70
Inline: True
```
```
In block/bio-integrity.c (ffffffff8142d1c3)
Location: include/linux/bio.h:70
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_enabled
```
```
In drivers/md/dm.c (ffffffff817033fe)
Location: include/linux/bio.h:70
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418c81)
Location: include/linux/bio.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_bio_prep
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:blk_dump_rq_flags
```
```
In block/blk-merge.c (ffffffff8141eed1)
Location: include/linux/bio.h:74
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:bio_data
```
```
In block/bounce.c (ffffffff814360eb)
Location: include/linux/bio.h:74
Inline: True
```
```
In drivers/md/dm.c (ffffffff817352cb)
Location: include/linux/bio.h:74
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff81426b61)
Location: include/linux/bio.h:74
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_bio_prep
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:blk_dump_rq_flags
```
```
In block/blk-merge.c (ffffffff8142d384)
Location: include/linux/bio.h:74
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff81442cf8)
Location: include/linux/bio.h:74
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff8174e507)
Location: include/linux/bio.h:74
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff81451b81)
Location: include/linux/bio.h:82
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_bio_prep
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:blk_dump_rq_flags
```
```
In block/blk-merge.c (ffffffff814585d4)
Location: include/linux/bio.h:82
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff8146f768)
Location: include/linux/bio.h:82
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff817c0528)
Location: include/linux/bio.h:82
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
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
In block/blk-core.c (ffffffff81484dc5)
Location: include/linux/bio.h:86
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_bio_prep
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff8148b412)
Location: include/linux/bio.h:86
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814a3a88)
Location: include/linux/bio.h:86
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff81808840)
Location: include/linux/bio.h:86
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149fca5)
Location: include/linux/bio.h:82
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_bio_prep
  - block/blk-core.c:blk_rq_bio_prep
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff814a50f2)
Location: include/linux/bio.h:82
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814be148)
Location: include/linux/bio.h:82
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff8183473a)
Location: include/linux/bio.h:82
Inline: True
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
In block/blk-core.c (ffffffff814cd3f0)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff814d31d2)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814ed098)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff8187650a)
Location: include/linux/bio.h:61
Inline: True
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
In block/blk-core.c (ffffffff814e66f4)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff814ec502)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff815064d8)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff818a830a)
Location: include/linux/bio.h:61
Inline: True
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
In block/blk-core.c (ffffffff81543924)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff8154bc52)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff81566e28)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/blk-crypto.c (ffffffff81581b8d)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In drivers/md/dm.c (ffffffff8197834a)
Location: include/linux/bio.h:61
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
In block/blk-core.c (ffffffff81560803)
Location: include/linux/bio.h:59
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff81567945)
Location: include/linux/bio.h:59
Inline: True
Inline callers:
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
```
```
In block/bounce.c (ffffffff81581c58)
Location: include/linux/bio.h:59
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/blk-crypto.c (ffffffff8159eb74)
Location: include/linux/bio.h:59
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In drivers/md/dm.c (ffffffff8197d02e)
Location: include/linux/bio.h:59
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_empty_flush
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
In block/blk-core.c (ffffffff81568e69)
Location: include/linux/bio.h:62
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff8156fbe0)
Location: include/linux/bio.h:62
Inline: True
Inline callers:
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-mq.c (0)
Location: include/linux/bio.h:62
Inline: False
```
```
In block/blk-crypto.c (ffffffff815a5953)
Location: include/linux/bio.h:62
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In drivers/md/dm.c (ffffffff81960f78)
Location: include/linux/bio.h:62
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_empty_flush
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
In block/blk-core.c (ffffffff815cd110)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff815d4280)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-mq.c (0)
Location: include/linux/bio.h:61
Inline: False
```
```
In block/blk-crypto.c (ffffffff8160e423)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In drivers/md/dm.c (ffffffff81a0ac18)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_empty_flush
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
In block/blk-merge.c (ffffffff816800a3)
Location: include/linux/bio.h:52
Inline: True
Inline callers:
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-mq.c (ffffffff81686f57)
Location: include/linux/bio.h:52
Inline: True
Inline callers:
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
```
In block/blk-crypto.c (ffffffff816c1abf)
Location: include/linux/bio.h:52
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
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
In block/blk-merge.c (ffffffff8173d463)
Location: include/linux/bio.h:52
Inline: True
Inline callers:
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-mq.c (ffffffff81744c3b)
Location: include/linux/bio.h:52
Inline: True
Inline callers:
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_dump_rq_flags
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-crypto.c (ffffffff81782caf)
Location: include/linux/bio.h:52
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
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
In block/blk-merge.c (ffffffff81779a00)
Location: include/linux/bio.h:54
Inline: True
Inline callers:
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-mq.c (ffffffff81780aab)
Location: include/linux/bio.h:54
Inline: True
Inline callers:
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_dump_rq_flags
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-crypto.c (ffffffff817c2ee3)
Location: include/linux/bio.h:54
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
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
In block/blk-merge.c (ffffffff817bbdd0)
Location: include/linux/bio.h:54
Inline: True
Inline callers:
  - block/blk-merge.c:bio_will_gap
```
```
In block/blk-mq.c (ffffffff817c3061)
Location: include/linux/bio.h:54
Inline: True
Inline callers:
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_dump_rq_flags
  - block/blk-mq.c:blk_dump_rq_flags
```
```
In block/blk-crypto.c (ffffffff81807b73)
Location: include/linux/bio.h:54
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
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
In block/blk-core.c (ffff8000105e3e10)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffff8000105eaf6c)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In drivers/md/dm.c (ffff800010afedbc)
Location: include/linux/bio.h:61
Inline: True
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
In block/blk-core.c (c0790fb8)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (c07974d4)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (c07b3978)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/mtd/mtd_blkdevs.c (c0a98730)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
  - drivers/mtd/mtd_blkdevs.c:mtd_blktrans_work
```
```
In drivers/md/dm.c (c0bddefc)
Location: include/linux/bio.h:61
Inline: True
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
In block/blk-core.c (c000000000777ab0)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (c000000000780290)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In drivers/md/dm.c (c000000000becfc4)
Location: include/linux/bio.h:61
Inline: True
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
In block/blk-core.c (ffffffe0004256b0)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffe00042b072)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In drivers/md/dm.c (ffffffe0006ee7d2)
Location: include/linux/bio.h:61
Inline: True
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
In block/blk-core.c (ffffffff814decd4)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff814e4ae2)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814feab8)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff8184e18a)
Location: include/linux/bio.h:61
Inline: True
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
In block/blk-core.c (ffffffff814cf674)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff814d52a3)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814eefc8)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff818157aa)
Location: include/linux/bio.h:61
Inline: True
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
In block/blk-core.c (ffffffff814dad64)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff814e0b72)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff814fab48)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff8189d7ba)
Location: include/linux/bio.h:61
Inline: True
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
In block/blk-core.c (ffffffff814f3af4)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
```
```
In block/blk-merge.c (ffffffff814f99f2)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
```
```
In block/bounce.c (ffffffff81513bf8)
Location: include/linux/bio.h:61
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In drivers/md/dm.c (ffffffff818b9b1a)
Location: include/linux/bio.h:61
Inline: True
```
</details>
</li>
</ul>

## Differences
