# Function: <code>bio_crypt_free_ctx</code>

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
In block/bio.c (ffffffff8153e245)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-core.c (ffffffff81545957)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-core.c:bio_attempt_back_merge
```
```
In block/blk-map.c (ffffffff81549db2)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-crypto-fallback.c (ffffffff81582eb2)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
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
In block/bio.c (ffffffff8155a56a)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-map.c (ffffffff81565835)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff81568e99)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-crypto-fallback.c (ffffffff8159fd52)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
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
In block/bio.c (ffffffff81562d4a)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-map.c (ffffffff8156de6b)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff81570bc9)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-crypto-fallback.c (ffffffff815a6b42)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
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
In block/bio.c (ffffffff815c69ba)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-map.c (ffffffff815d245b)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff815d5276)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-crypto-fallback.c (ffffffff8160f66c)
Location: block/blk-crypto-internal.h:106
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
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
In block/bio.c (ffffffff8167187c)
Location: block/blk-crypto-internal.h:118
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-map.c (ffffffff8167e164)
Location: block/blk-crypto-internal.h:118
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff81681043)
Location: block/blk-crypto-internal.h:118
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-crypto-fallback.c (ffffffff816c3f8c)
Location: block/blk-crypto-internal.h:118
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
In block/bio.c (ffffffff8172d0ec)
Location: block/blk-crypto-internal.h:132
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-map.c (ffffffff8173adf4)
Location: block/blk-crypto-internal.h:132
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8173e583)
Location: block/blk-crypto-internal.h:132
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-crypto-fallback.c (ffffffff8178547c)
Location: block/blk-crypto-internal.h:132
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
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
In block/bio.c (ffffffff8176948c)
Location: block/blk-crypto-internal.h:142
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-map.c (ffffffff81777496)
Location: block/blk-crypto-internal.h:142
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff8177aae3)
Location: block/blk-crypto-internal.h:142
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-crypto-fallback.c (ffffffff817c57dc)
Location: block/blk-crypto-internal.h:142
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
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
In block/bio.c (ffffffff817ab50c)
Location: block/blk-crypto-internal.h:142
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-map.c (ffffffff817b96b6)
Location: block/blk-crypto-internal.h:142
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_append_bio
```
```
In block/blk-merge.c (ffffffff817bcecd)
Location: block/blk-crypto-internal.h:142
Inline: True
Inline callers:
  - block/blk-merge.c:bio_attempt_back_merge
```
```
In block/blk-crypto-fallback.c (ffffffff8180a4cc)
Location: block/blk-crypto-internal.h:142
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_bio_prep
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
