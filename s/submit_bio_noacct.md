# Function: <code>submit_bio_noacct</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t submit_bio_noacct(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815619a0)
Location: block/blk-core.c:1044
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff815619a0-ffffffff81561a26: submit_bio_noacct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t submit_bio_noacct(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81569f60)
Location: block/blk-core.c:1030
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81569f60-ffffffff8156a18b: submit_bio_noacct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
blk_qc_t submit_bio_noacct(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cd800)
Location: block/blk-core.c:1019
Inline: True
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__blk_queue_split
  - block/blk-throttle.c:blk_throtl_dispatch_work_fn
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff815cd800-ffffffff815cd917: submit_bio_noacct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void submit_bio_noacct(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:756
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-merge.c:__blk_queue_split
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
**Symbols:**

```
ffffffff81e8b3f5-ffffffff81e8b4ad: submit_bio_noacct.cold (STB_LOCAL)
ffffffff81679360-ffffffff816798d0: submit_bio_noacct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void submit_bio_noacct(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:722
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
**Symbols:**

```
ffffffff82075c4b-ffffffff82075cd7: submit_bio_noacct.cold (STB_LOCAL)
ffffffff817357e0-ffffffff81735d7a: submit_bio_noacct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void submit_bio_noacct(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:720
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
**Symbols:**

```
ffffffff820f5ae3-ffffffff820f5b54: submit_bio_noacct.cold (STB_LOCAL)
ffffffff81771d90-ffffffff8177236b: submit_bio_noacct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void submit_bio_noacct(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:730
Inline: False
Direct callers:
  - block/bio.c:bio_alloc_rescue
  - block/blk-core.c:submit_bio
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/md.c:md_submit_discard_bio
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_submit_bio_remap
```
**Symbols:**

```
ffffffff821d2ece-ffffffff821d2f61: submit_bio_noacct.cold (STB_LOCAL)
ffffffff817b40d0-ffffffff817b4671: submit_bio_noacct (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>blk_qc_t</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
