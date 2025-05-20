# Function: <code>bio_has_crypt_ctx</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153daa3)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff815432ad)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:bio_attempt_front_merge
  - block/blk-core.c:bio_attempt_back_merge
```
```
In block/blk-map.c (ffffffff81549db2)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-mq.c (ffffffff8155108d)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
```
```
In block/bounce.c (ffffffff815667db)
Location: include/linux/blk-crypto.h:79
Inline: True
```
```
In block/bio-integrity.c (ffffffff8157658c)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In block/blk-crypto-fallback.c (ffffffff81582eb2)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/md/dm.c (ffffffff819770be)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_bio
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
In block/bio.c (ffffffff8155a623)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff8155fafb)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-map.c (ffffffff81565835)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff81568f77)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-mq.c (ffffffff8156ef49)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/bounce.c (ffffffff815816f0)
Location: include/linux/blk-crypto.h:79
Inline: True
```
```
In block/bio-integrity.c (ffffffff815934bc)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In block/blk-crypto-fallback.c (ffffffff8159fd52)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/md/dm.c (ffffffff8197bcbe)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_bio
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
In block/bio.c (ffffffff81562df3)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff815687eb)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-map.c (ffffffff8156de6b)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff81570e3f)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-mq.c (ffffffff81576b29)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/bio-integrity.c (ffffffff8159a2d2)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In block/blk-crypto-fallback.c (ffffffff815a6b42)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/md/dm.c (ffffffff819611dc)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff815c6a63)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio.c:bio_advance
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff815ccdcb)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
  - block/blk-core.c:__submit_bio
```
```
In block/blk-map.c (ffffffff815d245b)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff815d54ea)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-mq.c (ffffffff815db7d9)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/bio-integrity.c (ffffffff81602432)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In block/blk-crypto-fallback.c (ffffffff8160f66c)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/md/dm.c (ffffffff81a0adfc)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
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
In block/bio.c (ffffffff81671963)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_clone
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81678b29)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
```
```
In block/blk-map.c (ffffffff8167e164)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8168130d)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_front_merge
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-mq.c (ffffffff816846e9)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/bio-integrity.c (ffffffff816b50a2)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In block/blk-crypto-fallback.c (ffffffff816c3f8c)
Location: include/linux/blk-crypto.h:79
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
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
In block/bio.c (ffffffff8172d1f3)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_clone
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81734fb9)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
```
```
In block/blk-map.c (ffffffff8173adf4)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8173e583)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:bio_crypt_do_front_merge
```
```
In block/blk-mq.c (ffffffff81742099)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/bio-integrity.c (ffffffff81774bd2)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In block/blk-crypto-fallback.c (ffffffff8178547c)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d1fe04)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
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
In block/bio.c (ffffffff81769593)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_clone
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff817714f9)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
```
```
In block/blk-map.c (ffffffff81777496)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8177aae3)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:bio_crypt_do_front_merge
```
```
In block/blk-mq.c (ffffffff8177da6d)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/bio-integrity.c (ffffffff817b48f2)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In block/blk-crypto-fallback.c (ffffffff817c57dc)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/md/dm-io-rewind.c (ffffffff81d88feb)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
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
In block/bio.c (ffffffff817ab613)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/bio.c:__bio_advance
  - block/bio.c:__bio_clone
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff817b3839)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
```
```
In block/blk-map.c (ffffffff817b96b6)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff817bcecd)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
  - block/blk-merge.c:bio_crypt_do_front_merge
```
```
In block/blk-mq.c (ffffffff817bfdfa)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_mq_submit_bio
```
```
In block/bio-integrity.c (ffffffff817f8912)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_alloc
```
```
In block/blk-crypto-fallback.c (ffffffff8180a4cc)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
```
```
In drivers/md/dm-io-rewind.c (ffffffff81e4072b)
Location: include/linux/blk-crypto.h:77
Inline: True
Inline callers:
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
