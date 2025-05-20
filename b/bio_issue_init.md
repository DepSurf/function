# Function: <code>bio_issue_init</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498297)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8149d637)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814be44a)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
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
In block/bio.c (ffffffff814c6114)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cb87c)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814ecbd4)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff814de517)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814e4b3f)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff81506024)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff8153e036)
Location: include/linux/blk_types.h:144
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff81542bbe)
Location: include/linux/blk_types.h:144
Inline: True
Inline callers:
  - block/blk-core.c:blkcg_bio_issue_check
```
```
In block/bounce.c (ffffffff8156684b)
Location: include/linux/blk_types.h:144
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff8158291d)
Location: include/linux/blk_types.h:144
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In block/bio.c (ffffffff8155a01b)
Location: include/linux/blk_types.h:210
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8156017b)
Location: include/linux/blk_types.h:210
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/bounce.c (ffffffff81581752)
Location: include/linux/blk_types.h:210
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff8159f807)
Location: include/linux/blk_types.h:210
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In block/bio.c (ffffffff8156293c)
Location: include/linux/blk_types.h:210
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff81568309)
Location: include/linux/blk_types.h:210
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-crypto-fallback.c (ffffffff815a6525)
Location: include/linux/blk_types.h:210
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In block/bio.c (ffffffff815c6641)
Location: include/linux/blk_types.h:202
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff815cc8f6)
Location: include/linux/blk_types.h:202
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-crypto-fallback.c (ffffffff8160f029)
Location: include/linux/blk_types.h:202
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In block/blk-core.c (ffffffff816794f2)
Location: include/linux/blk_types.h:234
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff816804b0)
Location: include/linux/blk_types.h:234
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (ffffffff81735643)
Location: include/linux/blk_types.h:234
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-merge.c (ffffffff8173d8d2)
Location: include/linux/blk_types.h:234
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
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
In block/blk-core.c (ffffffff81771be3)
Location: include/linux/blk_types.h:247
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-merge.c (ffffffff81779e4f)
Location: include/linux/blk_types.h:247
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
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
In block/blk-core.c (ffffffff817b3f23)
Location: include/linux/blk_types.h:246
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-merge.c (ffffffff817bc22f)
Location: include/linux/blk_types.h:246
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
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
In block/bio.c (ffff8000105db95c)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffff8000105e2e54)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/bio.c (c0788510)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (c078f1dc)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (c07b3334)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (c00000000076b8ac)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (c000000000775448)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/bio.c (ffffffe00041e56e)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffe00042410a)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/bio.c (ffffffff814d6af7)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814dd11f)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814fe604)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff814c74b7)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cdaca)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814eeb14)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff814d2b87)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814d91af)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814fa694)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff814eb70d)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814f1dc4)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff8151381f)
Location: include/linux/blk_types.h:131
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
</li>
</ul>

## Differences
