# Function: <code>bvec_gap_to_prev</code>

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
In block/bio.c (ffffffff813b0a9c)
Location: include/linux/blkdev.h:1381
Inline: True
```
```
In block/blk-merge.c (ffffffff813c069e)
Location: include/linux/blkdev.h:1381
Inline: True
Inline callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:ll_front_merge_fn
```
```
In block/bio-integrity.c (ffffffff813e7211)
Location: include/linux/blkdev.h:1381
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff813e831a)
Location: include/linux/blkdev.h:1381
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
In block/bio.c (ffffffff813f43e9)
Location: include/linux/blkdev.h:1410
Inline: True
```
```
In block/blk-merge.c (ffffffff81405265)
Location: include/linux/blkdev.h:1410
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff8142d491)
Location: include/linux/blkdev.h:1410
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8142e594)
Location: include/linux/blkdev.h:1410
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
In block/bio.c (ffffffff8140ddd9)
Location: include/linux/blkdev.h:1615
Inline: True
```
```
In block/blk-merge.c (ffffffff8141f182)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff81447271)
Location: include/linux/blkdev.h:1615
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8144832f)
Location: include/linux/blkdev.h:1615
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
In block/bio.c (ffffffff8141ba39)
Location: include/linux/blkdev.h:1640
Inline: True
```
```
In block/blk-merge.c (ffffffff8142cfc0)
Location: include/linux/blkdev.h:1640
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814556b1)
Location: include/linux/blkdev.h:1640
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff81456523)
Location: include/linux/blkdev.h:1640
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
In block/bio.c (ffffffff814466f2)
Location: include/linux/blkdev.h:1655
Inline: True
```
```
In block/blk-merge.c (ffffffff814581c8)
Location: include/linux/blkdev.h:1655
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff8148131c)
Location: include/linux/blkdev.h:1655
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff81482173)
Location: include/linux/blkdev.h:1655
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
In block/bio.c (ffffffff8147955e)
Location: include/linux/blkdev.h:1704
Inline: True
```
```
In block/blk-merge.c (ffffffff8148b45d)
Location: include/linux/blkdev.h:1704
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814b5f3c)
Location: include/linux/blkdev.h:1704
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff814b6d42)
Location: include/linux/blkdev.h:1704
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
In block/bio.c (ffffffff81497552)
Location: block/blk.h:96
Inline: True
```
```
In block/blk-merge.c (ffffffff814a513d)
Location: block/blk.h:96
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814c97fc)
Location: block/blk.h:96
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff814ca552)
Location: block/blk.h:96
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
In block/bio.c (ffffffff814c4ea8)
Location: block/blk.h:94
Inline: True
Inline callers:
  - block/bio.c:__bio_add_pc_page
```
```
In block/blk-merge.c (ffffffff814d321c)
Location: block/blk.h:94
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814f7f0c)
Location: block/blk.h:94
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff814f8e16)
Location: block/blk.h:94
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
In block/bio.c (ffffffff814ddedc)
Location: block/blk.h:102
Inline: True
```
```
In block/blk-merge.c (ffffffff814ec54c)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff81515d9c)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff81516cc6)
Location: block/blk.h:102
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
In block/bio.c (ffffffff8153f5a8)
Location: block/blk.h:93
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-merge.c (ffffffff8154c51f)
Location: block/blk.h:93
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff815764ff)
Location: block/blk.h:93
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff81577477)
Location: block/blk.h:93
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
In block/bio.c (ffffffff8155bdb8)
Location: block/blk.h:85
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-merge.c (ffffffff81567dd9)
Location: block/blk.h:85
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff8159343f)
Location: block/blk.h:85
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff815945d6)
Location: block/blk.h:85
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
In block/bio.c (ffffffff81564416)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-merge.c (ffffffff81570c7d)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff8159a24f)
Location: block/blk.h:91
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8159b3ba)
Location: block/blk.h:91
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
In block/bio.c (ffffffff815c88a6)
Location: block/blk.h:89
Inline: True
```
```
In block/blk-merge.c (ffffffff815d532d)
Location: block/blk.h:89
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff816021df)
Location: block/blk.h:89
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8160361a)
Location: block/blk.h:89
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
In block/bio.c (ffffffff8167373a)
Location: block/blk.h:116
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-merge.c (ffffffff8168111a)
Location: block/blk.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff816b4d7f)
Location: block/blk.h:116
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff816b6373)
Location: block/blk.h:116
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
In block/bio.c (ffffffff8172f2fa)
Location: block/blk.h:113
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-map.c (ffffffff8173c520)
Location: block/blk.h:113
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff8173e6a5)
Location: block/blk.h:113
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:bio_split_rw
```
```
In block/bio-integrity.c (ffffffff8177485b)
Location: block/blk.h:113
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff817761a3)
Location: block/blk.h:113
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
In block/bio.c (ffffffff8176b5e1)
Location: block/blk.h:117
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-map.c (ffffffff81778acf)
Location: block/blk.h:117
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff8177ac05)
Location: block/blk.h:117
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:bio_split_rw
```
```
In block/bio-integrity.c (ffffffff817b45ae)
Location: block/blk.h:117
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff817b5e53)
Location: block/blk.h:117
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
In block/bio.c (ffffffff817ada81)
Location: block/blk.h:116
Inline: True
Inline callers:
  - block/bio.c:bio_add_hw_page
```
```
In block/blk-map.c (ffffffff817bae90)
Location: block/blk.h:116
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_map_user_iov
```
```
In block/blk-merge.c (ffffffff817bcfe5)
Location: block/blk.h:116
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:bio_split_rw
```
```
In block/bio-integrity.c (ffffffff817f87f9)
Location: block/blk.h:116
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff817fa863)
Location: block/blk.h:116
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
In block/bio.c (ffff8000105da500)
Location: block/blk.h:102
Inline: True
```
```
In block/blk-merge.c (ffff8000105eafb8)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffff80001061cf20)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffff80001061e138)
Location: block/blk.h:102
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
In block/bio.c (c0788210)
Location: block/blk.h:102
Inline: True
```
```
In block/blk-merge.c (c0797520)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (c07c4b70)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (c07c5c00)
Location: block/blk.h:102
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
In block/bio.c (c00000000076b35c)
Location: block/blk.h:102
Inline: True
```
```
In block/blk-merge.c (c0000000007804e4)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (c0000000007bbb34)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (c0000000007bd268)
Location: block/blk.h:102
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
In block/bio.c (ffffffe00041e25a)
Location: block/blk.h:102
Inline: True
```
```
In block/blk-merge.c (ffffffe00042b22a)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffe00044fdea)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffe000450e08)
Location: block/blk.h:102
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
In block/bio.c (ffffffff814d64bc)
Location: block/blk.h:102
Inline: True
```
```
In block/blk-merge.c (ffffffff814e4b2c)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff8150e37c)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8150f2a6)
Location: block/blk.h:102
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
In block/bio.c (ffffffff814c6e1c)
Location: block/blk.h:102
Inline: True
```
```
In block/blk-merge.c (ffffffff814d52e9)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff814fe7ac)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff814ff6d6)
Location: block/blk.h:102
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
In block/bio.c (ffffffff814d254c)
Location: block/blk.h:102
Inline: True
```
```
In block/blk-merge.c (ffffffff814e0bbc)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff8150a40c)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff8150b336)
Location: block/blk.h:102
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
In block/bio.c (ffffffff814eb06c)
Location: block/blk.h:102
Inline: True
```
```
In block/blk-merge.c (ffffffff814f9a3c)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/blk-merge.c:ll_front_merge_fn
  - block/blk-merge.c:ll_back_merge_fn
  - block/blk-merge.c:__blk_queue_split
```
```
In block/bio-integrity.c (ffffffff81523a7c)
Location: block/blk.h:102
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_add_page
```
```
In block/blk-integrity.c (ffffffff815249d6)
Location: block/blk.h:102
Inline: True
```
</details>
</li>
</ul>

## Differences
