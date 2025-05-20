# Function: <code>bio_advance_iter_single</code>

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
In block/bio.c (ffffffff8155ae76)
Location: include/linux/bio.h:152
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff815657df)
Location: include/linux/bio.h:152
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff81567336)
Location: include/linux/bio.h:152
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bounce.c (ffffffff815819aa)
Location: include/linux/bio.h:152
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
  - block/bounce.c:copy_to_high_bio_irq
```
```
In block/bio-integrity.c (ffffffff81593335)
Location: include/linux/bio.h:152
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-crypto.c (ffffffff8159e822)
Location: include/linux/bio.h:152
Inline: True
Inline callers:
  - block/blk-crypto.c:bio_crypt_check_alignment
```
```
In block/blk-crypto-fallback.c (ffffffff8159f59d)
Location: include/linux/bio.h:152
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/block/loop.c (ffffffff817fc636)
Location: include/linux/bio.h:152
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
In block/bio.c (ffffffff815636a6)
Location: include/linux/bio.h:155
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8156de29)
Location: include/linux/bio.h:155
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8156f69e)
Location: include/linux/bio.h:155
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff8159a137)
Location: include/linux/bio.h:155
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-crypto.c (ffffffff815a59f9)
Location: include/linux/bio.h:155
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff815a62a0)
Location: include/linux/bio.h:155
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/block/loop.c (ffffffff817e29d0)
Location: include/linux/bio.h:155
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
In block/bio.c (ffffffff815c6fef)
Location: include/linux/bio.h:154
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff815d2419)
Location: include/linux/bio.h:154
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff815d3d47)
Location: include/linux/bio.h:154
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff81602397)
Location: include/linux/bio.h:154
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-crypto.c (ffffffff8160e4c9)
Location: include/linux/bio.h:154
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff8160edc0)
Location: include/linux/bio.h:154
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/block/loop.c (ffffffff8186edce)
Location: include/linux/bio.h:154
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
In block/bio.c (ffffffff81671efd)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:guard_bio_eod
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8167e11f)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8167fb72)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_bio_segment_split
  - block/blk-merge.c:blk_bio_segment_split
```
```
In block/bio-integrity.c (ffffffff816b4ee9)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-crypto.c (ffffffff816c1b73)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff816c365e)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/block/loop.c (ffffffff819b7283)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
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
In block/bio.c (ffffffff8172d67c)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:guard_bio_eod
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff8173adaf)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8173cf11)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_rw
  - block/blk-merge.c:bio_split_rw
```
```
In block/bio-integrity.c (ffffffff81774a73)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-crypto.c (ffffffff81782d63)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff81784af2)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/block/loop.c (ffffffff81b2c5e4)
Location: include/linux/bio.h:109
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
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
In block/bio.c (ffffffff81769a2f)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:guard_bio_eod
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio
  - block/bio.c:zero_fill_bio
```
```
In block/blk-map.c (ffffffff81777450)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8177949a)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_rw
  - block/blk-merge.c:bio_split_rw
```
```
In block/bio-integrity.c (ffffffff817b4799)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-crypto.c (ffffffff817c2faa)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff817c4e52)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/block/loop.c (ffffffff81b7c847)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
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
In block/bio.c (ffffffff817abbdf)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:bio_copy_data_iter
  - block/bio.c:guard_bio_eod
  - block/bio.c:guard_bio_eod
  - block/bio.c:zero_fill_bio_iter
  - block/bio.c:zero_fill_bio_iter
```
```
In block/blk-map.c (ffffffff817b9670)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff817bb86a)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:__blk_bios_map_sg
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:blk_recalc_rq_segments
  - block/blk-merge.c:bio_split_rw
  - block/blk-merge.c:bio_split_rw
```
```
In block/bio-integrity.c (ffffffff817f85d9)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
```
```
In block/blk-crypto.c (ffffffff81807c3a)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_bio_prep
```
```
In block/blk-crypto-fallback.c (ffffffff81809b42)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
```
```
In drivers/block/loop.c (ffffffff81bd0777)
Location: include/linux/bio.h:111
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_read_simple
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
