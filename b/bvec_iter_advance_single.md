# Function: <code>bvec_iter_advance_single</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155aff1)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff815657e6)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff81567480)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bounce.c (ffffffff815819b1)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff8159335b)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff815941a2)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff81594c0b)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-crypto.c (ffffffff8159e841)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_check_alignment
```
```
In block/blk-crypto-fallback.c (ffffffff8159f5be)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In lib/iov_iter.c (ffffffff815a593a)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_get_pages_alloc
  - lib/iov_iter.c:iov_iter_get_pages
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff817fc65e)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_read_simple
  - drivers/block/loop.c:lo_write_transfer
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
In block/bio.c (ffffffff81563822)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8156de30)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8156f84f)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff8159a15d)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff8159af81)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff8159b9ce)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-crypto.c (ffffffff815a5a01)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff815a62c1)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In lib/iov_iter.c (ffffffff815aca3a)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_for_each_range
  - lib/iov_iter.c:iov_iter_npages
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter_full
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:iov_iter_gap_alignment
  - lib/iov_iter.c:iov_iter_alignment
  - lib/iov_iter.c:iov_iter_advance
  - lib/iov_iter.c:iov_iter_copy_from_user_atomic
  - lib/iov_iter.c:iov_iter_zero
  - lib/iov_iter.c:_copy_from_iter_full_nocache
  - lib/iov_iter.c:_copy_from_iter_flushcache
  - lib/iov_iter.c:_copy_from_iter_nocache
  - lib/iov_iter.c:_copy_from_iter_full
  - lib/iov_iter.c:_copy_from_iter
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
```
In drivers/block/loop.c (ffffffff817e29ee)
Location: include/linux/bvec.h:128
Inline: True
Inline callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
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
In block/bio.c (ffffffff815c7165)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff815d2420)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff815d3ef8)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff816023bd)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff816031e2)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff81603979)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-crypto.c (ffffffff8160e4d1)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff8160ede1)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/block/loop.c (ffffffff8186edec)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:lo_read_transfer
  - drivers/block/loop.c:lo_write_transfer
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
In block/bio.c (ffffffff81671f1f)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8167e126)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8167fb88)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff816b4efe)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff816b5a62)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff816b6c21)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-crypto.c (ffffffff816c1b73)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff816c3677)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/block/loop.c (ffffffff819b7290)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
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
In block/bio.c (ffffffff8172d837)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8173adb6)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8173d0ca)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_rw
```
```
In block/bio-integrity.c (ffffffff81774a90)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff81775d12)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff81776be1)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-crypto.c (ffffffff81782d63)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff81784b0b)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In io_uring/net.c (ffffffff81795c83)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/block/loop.c (ffffffff81b2c5f9)
Location: include/linux/bvec.h:129
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
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
In block/bio.c (ffffffff81769b92)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff81777457)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff81779666)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_rw
```
```
In block/bio-integrity.c (ffffffff817b47aa)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff817b59c2)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff817b67b8)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-crypto.c (ffffffff817c2fb1)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff817c4e88)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In io_uring/net.c (ffffffff817d6915)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/block/loop.c (ffffffff81b7c850)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
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
In block/bio.c (ffffffff817abd42)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff817b9677)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff817bba36)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_rw
```
```
In block/bio-integrity.c (ffffffff817f85ea)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-integrity.c (ffffffff817fa3d2)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_rq_map_integrity_sg
  - block/blk-integrity.c:blk_rq_count_integrity_sg
```
```
In block/t10-pi.c (ffffffff817fb1c8)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/t10-pi.c:ext_pi_type1_complete
  - block/t10-pi.c:ext_pi_type1_prepare
  - block/t10-pi.c:t10_pi_type1_complete
  - block/t10-pi.c:t10_pi_type1_prepare
```
```
In block/blk-crypto.c (ffffffff81807c41)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff81809b78)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In io_uring/net.c (ffffffff8181aae5)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - io_uring/net.c:io_sg_from_iter
```
```
In drivers/block/loop.c (ffffffff81bd0780)
Location: include/linux/bvec.h:168
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
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
