# Function: <code>bio_split</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b1f30)
Location: block/bio.c:1785
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
```
**Symbols:**

```
ffffffff813b1f30-ffffffff813b1fb9: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f6b90)
Location: block/bio.c:1780
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
```
**Symbols:**

```
ffffffff813f6b90-ffffffff813f6c1e: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81410210)
Location: block/bio.c:1835
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
```
**Symbols:**

```
ffffffff81410210-ffffffff81410282: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141dc50)
Location: block/bio.c:1857
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff8141dc50-ffffffff8141dcd0: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814476e0)
Location: block/bio.c:1821
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff814476e0-ffffffff81447760: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147a7e0)
Location: block/bio.c:1878
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
  - block/bounce.c:blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8147a7e0-ffffffff8147a865: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498b00)
Location: block/bio.c:1811
Inline: False
Direct callers:
  - block/blk-merge.c:blk_queue_split
  - block/blk-merge.c:blk_queue_split
  - block/bounce.c:blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81498b00-ffffffff81498b7b: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6ae0)
Location: block/bio.c:1848
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814c6ae0-ffffffff814c6b5a: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814df8f0)
Location: block/bio.c:1890
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814df8f0-ffffffff814df96a: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f380)
Location: block/bio.c:1465
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8153f380-ffffffff8153f406: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155bb80)
Location: block/bio.c:1468
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
  - block/bounce.c:__blk_queue_bounce
  - block/blk-crypto-fallback.c:blk_crypto_split_bio_if_needed
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8155bb80-ffffffff8155bc06: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81564210)
Location: block/bio.c:1431
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81564210-ffffffff81564296: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c8500)
Location: block/bio.c:1513
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff815c8500-ffffffff815c8586: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816733c0)
Location: block/bio.c:1571
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_segment_split
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - drivers/md/dm.c:dm_split_and_process_bio
```
**Symbols:**

```
ffffffff816733c0-ffffffff816734ab: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172ef50)
Location: block/bio.c:1634
Inline: False
Direct callers:
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-merge.c:bio_split_rw
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8172ef50-ffffffff8172f03b: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176b180)
Location: block/bio.c:1619
Inline: False
Direct callers:
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-merge.c:bio_split_rw
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff8176b180-ffffffff8176b288: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ad610)
Location: block/bio.c:1626
Inline: False
Direct callers:
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-merge.c:__bio_split_to_limits
  - block/blk-merge.c:bio_split_rw
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
```
**Symbols:**

```
ffffffff817ad610-ffffffff817ad718: bio_split (STB_GLOBAL)
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
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dc430)
Location: block/bio.c:1890
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffff8000105dc430-ffff8000105dc4dc: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c07898ac)
Location: block/bio.c:1890
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:blk_bio_discard_split
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c07898ac-c0789940: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076d450)
Location: block/bio.c:1890
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c00000000076d450-c00000000076d530: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041f81e)
Location: block/bio.c:1890
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffe00041f81e-ffffffe00041f8b8: bio_split (STB_GLOBAL)
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
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d7ed0)
Location: block/bio.c:1890
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814d7ed0-ffffffff814d7f4a: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c8880)
Location: block/bio.c:1890
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814c8880-ffffffff814c88fa: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d3f60)
Location: block/bio.c:1890
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814d3f60-ffffffff814d3fda: bio_split (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bio *bio_split(struct bio *bio, int sectors, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ecaf0)
Location: block/bio.c:1890
Inline: False
Direct callers:
  - block/blk-merge.c:__blk_queue_split
  - block/blk-merge.c:__blk_queue_split
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:dm_process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814ecaf0-ffffffff814ecb6a: bio_split (STB_GLOBAL)
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
