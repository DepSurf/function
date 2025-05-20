# Function: <code>__bvec_gap_to_prev</code>

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
In block/bio.c (ffffffff813b0aa8)
Location: include/linux/blkdev.h:1370
Inline: True
```
```
In block/blk-merge.c (ffffffff813c06a3)
Location: include/linux/blkdev.h:1370
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:attempt_merge
```
```
In block/bio-integrity.c (ffffffff813e7218)
Location: include/linux/blkdev.h:1370
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff813e8323)
Location: include/linux/blkdev.h:1370
Inline: True
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
In block/bio.c (ffffffff813f4494)
Location: include/linux/blkdev.h:1399
Inline: True
```
```
In block/blk-merge.c (ffffffff81405104)
Location: include/linux/blkdev.h:1399
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff8142d498)
Location: include/linux/blkdev.h:1399
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8142e59d)
Location: include/linux/blkdev.h:1399
Inline: True
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
In block/bio.c (ffffffff8140de84)
Location: include/linux/blkdev.h:1604
Inline: True
```
```
In block/blk-merge.c (ffffffff8141efdf)
Location: include/linux/blkdev.h:1604
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff81447278)
Location: include/linux/blkdev.h:1604
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff81448338)
Location: include/linux/blkdev.h:1604
Inline: True
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
In block/bio.c (ffffffff8141badb)
Location: include/linux/blkdev.h:1629
Inline: True
```
```
In block/blk-merge.c (ffffffff8142d500)
Location: include/linux/blkdev.h:1629
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814556b8)
Location: include/linux/blkdev.h:1629
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8145652e)
Location: include/linux/blkdev.h:1629
Inline: True
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
In block/bio.c (ffffffff8144679b)
Location: include/linux/blkdev.h:1644
Inline: True
```
```
In block/blk-merge.c (ffffffff81458750)
Location: include/linux/blkdev.h:1644
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff81481331)
Location: include/linux/blkdev.h:1644
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8148218e)
Location: include/linux/blkdev.h:1644
Inline: True
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
In block/bio.c (ffffffff8147956a)
Location: include/linux/blkdev.h:1693
Inline: True
```
```
In block/blk-merge.c (ffffffff8148b6e3)
Location: include/linux/blkdev.h:1693
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814b5f53)
Location: include/linux/blkdev.h:1693
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff814b6d56)
Location: include/linux/blkdev.h:1693
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
In block/bio.c (ffffffff8149755e)
Location: block/blk.h:85
Inline: True
```
```
In block/blk-merge.c (ffffffff814a5389)
Location: block/blk.h:85
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814c9813)
Location: block/blk.h:85
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff814ca566)
Location: block/blk.h:85
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
In block/bio.c (ffffffff814c4eb8)
Location: block/blk.h:83
Inline: True
Inline callers:
  - block/bio.c:__bio_add_pc_page
```
```
In block/blk-merge.c (ffffffff814d355c)
Location: block/blk.h:83
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814f7f23)
Location: block/blk.h:83
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff814f8e2b)
Location: block/blk.h:83
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
In block/bio.c (ffffffff814ddeec)
Location: block/blk.h:91
Inline: True
```
```
In block/blk-merge.c (ffffffff814ec88c)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff81515db3)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff81516cdb)
Location: block/blk.h:91
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
In block/bio.c (ffffffff8153f5b8)
Location: block/blk.h:82
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-merge.c (ffffffff8154c7d0)
Location: block/blk.h:82
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff81576516)
Location: block/blk.h:82
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8157748c)
Location: block/blk.h:82
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
In block/bio.c (ffffffff8155bdc8)
Location: block/blk.h:74
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-merge.c (ffffffff81567b8b)
Location: block/blk.h:74
Inline: True
Inline callers:
  - block/blk-merge.c:ll_merge_requests_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff81593453)
Location: block/blk.h:74
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff815945eb)
Location: block/blk.h:74
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_rq
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
In block/bio.c (ffffffff81564426)
Location: block/blk.h:80
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-merge.c (ffffffff81570c95)
Location: block/blk.h:80
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_bio_segment_split
  - block/blk-merge.c:bio_will_gap
```
```
In block/bio-integrity.c (ffffffff8159a26a)
Location: block/blk.h:80
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8159b3cf)
Location: block/blk.h:80
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_rq
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
In block/bio.c (ffffffff815c88b6)
Location: block/blk.h:78
Inline: True
```
```
In block/blk-merge.c (ffffffff815d5345)
Location: block/blk.h:78
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_bio_segment_split
  - block/blk-merge.c:bio_will_gap
```
```
In block/bio-integrity.c (ffffffff816021fa)
Location: block/blk.h:78
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8160362f)
Location: block/blk.h:78
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_rq
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
In block/bio.c (ffffffff8167374a)
Location: block/blk.h:105
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-merge.c (ffffffff81681132)
Location: block/blk.h:105
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
  - block/blk-merge.c:bio_will_gap
```
```
In block/bio-integrity.c (ffffffff816b4d96)
Location: block/blk.h:105
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff816b6387)
Location: block/blk.h:105
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_rq
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
In block/bio.c (ffffffff8172f30a)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-map.c (ffffffff8173c52c)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff8173e6bd)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:bio_split_rw
  - block/blk-merge.c:bio_will_gap
```
```
In block/bio-integrity.c (ffffffff81774872)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff817761b7)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_rq
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
In block/bio.c (ffffffff8176b5ed)
Location: block/blk.h:106
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-map.c (ffffffff81778adb)
Location: block/blk.h:106
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff8177ac1d)
Location: block/blk.h:106
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:bio_split_rw
  - block/blk-merge.c:bio_will_gap
```
```
In block/bio-integrity.c (ffffffff817b45ba)
Location: block/blk.h:106
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff817b5e67)
Location: block/blk.h:106
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_rq
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
In block/bio.c (ffffffff817ada8d)
Location: block/blk.h:105
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-map.c (ffffffff817bae9c)
Location: block/blk.h:105
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff817bcffd)
Location: block/blk.h:105
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:bio_split_rw
  - block/blk-merge.c:bio_will_gap
```
```
In block/bio-integrity.c (ffffffff817f8805)
Location: block/blk.h:105
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff817fa877)
Location: block/blk.h:105
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_merge_rq
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
In block/bio.c (ffff8000105da508)
Location: block/blk.h:91
Inline: True
```
```
In block/blk-merge.c (ffff8000105eb2e8)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffff80001061cf30)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffff80001061e148)
Location: block/blk.h:91
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
In block/bio.c (c078821c)
Location: block/blk.h:91
Inline: True
```
```
In block/blk-merge.c (c0797824)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (c07c4b84)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (c07c5c10)
Location: block/blk.h:91
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
In block/bio.c (c00000000076b368)
Location: block/blk.h:91
Inline: True
```
```
In block/blk-merge.c (c000000000780720)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (c0000000007bbb48)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (c0000000007bd27c)
Location: block/blk.h:91
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
In block/bio.c (ffffffe00041e260)
Location: block/blk.h:91
Inline: True
```
```
In block/blk-merge.c (ffffffe00042b1ec)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffe00044fdf6)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffe000450e12)
Location: block/blk.h:91
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
In block/bio.c (ffffffff814d64cc)
Location: block/blk.h:91
Inline: True
```
```
In block/blk-merge.c (ffffffff814e4e6c)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff8150e393)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8150f2bb)
Location: block/blk.h:91
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
In block/bio.c (ffffffff814c6e2c)
Location: block/blk.h:91
Inline: True
```
```
In block/blk-merge.c (ffffffff814d55a7)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814fe7c3)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff814ff6eb)
Location: block/blk.h:91
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
In block/bio.c (ffffffff814d255c)
Location: block/blk.h:91
Inline: True
```
```
In block/blk-merge.c (ffffffff814e0efc)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff8150a423)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8150b34b)
Location: block/blk.h:91
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
In block/bio.c (ffffffff814eb07c)
Location: block/blk.h:91
Inline: True
```
```
In block/blk-merge.c (ffffffff814f9d7c)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff81523a93)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff815249eb)
Location: block/blk.h:91
Inline: True
```
</details>
</li>
</ul>

## Differences
