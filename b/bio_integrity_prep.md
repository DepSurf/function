# Function: <code>bio_integrity_prep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff813e7800)
Location: block/bio-integrity.c:269
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813e7800-ffffffff813e7a39: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8142da70)
Location: block/bio-integrity.c:269
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8142da70-ffffffff8142dcc4: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81447850)
Location: block/bio-integrity.c:269
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81447850-ffffffff81447a8f: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81455be0)
Location: block/bio-integrity.c:236
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81455be0-ffffffff81455e21: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81481840)
Location: block/bio-integrity.c:236
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81481840-ffffffff81481a81: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:236
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814b68a6-ffffffff814b68df: bio_integrity_prep.cold.13 (STB_LOCAL)
ffffffff814b6300-ffffffff814b651d: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:214
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814ca0b2-ffffffff814ca0e9: bio_integrity_prep.cold.13 (STB_LOCAL)
ffffffff814c9c00-ffffffff814c9e7e: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814f8973-ffffffff814f89be: bio_integrity_prep.cold (STB_LOCAL)
ffffffff814f8520-ffffffff814f8784: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81516803-ffffffff8151684e: bio_integrity_prep.cold (STB_LOCAL)
ffffffff815162a0-ffffffff81516501: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:208
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81576f76-ffffffff81576fb9: bio_integrity_prep.cold (STB_LOCAL)
ffffffff81576a20-ffffffff81576c86: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:208
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81bf3c7d-ffffffff81bf3cc0: bio_integrity_prep.cold (STB_LOCAL)
ffffffff815936b0-ffffffff81593913: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:203
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81be5adf-ffffffff81be5b22: bio_integrity_prep.cold (STB_LOCAL)
ffffffff8159a490-ffffffff8159a6f5: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:198
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81cd9ffb-ffffffff81cda05d: bio_integrity_prep.cold (STB_LOCAL)
ffffffff81602670-ffffffff816028de: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81e8dae2-ffffffff81e8db43: bio_integrity_prep.cold (STB_LOCAL)
ffffffff816b51e0-ffffffff816b542b: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff82077013-ffffffff82077033: bio_integrity_prep.cold (STB_LOCAL)
ffffffff81774d20-ffffffff81774fc4: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:211
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff820f7069-ffffffff820f7089: bio_integrity_prep.cold (STB_LOCAL)
ffffffff817b4a40-ffffffff817b4ce1: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:426
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff821d485e-ffffffff821d487e: bio_integrity_prep.cold (STB_LOCAL)
ffffffff817f8af0-ffffffff817f8d8d: bio_integrity_prep (STB_GLOBAL)
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
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffff80001061d4c8)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffff80001061d4c8-ffff80001061d760: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c07c50c0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c07c50c0-c07c5348: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c0000000007bc2a0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c0000000007bc2a0-c0000000007bc63c: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffe000450308)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffe000450308-ffffffe000450544: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8150ede3-ffffffff8150ee2e: bio_integrity_prep.cold (STB_LOCAL)
ffffffff8150e880-ffffffff8150eae1: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
  - drivers/nvdimm/btt.c:btt_make_request
```
**Symbols:**

```
ffffffff814ff213-ffffffff814ff25e: bio_integrity_prep.cold (STB_LOCAL)
ffffffff814fecb0-ffffffff814fef11: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8150ae73-ffffffff8150aebe: bio_integrity_prep.cold (STB_LOCAL)
ffffffff8150a910-ffffffff8150ab71: bio_integrity_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool bio_integrity_prep(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:199
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81524513-ffffffff8152455e: bio_integrity_prep.cold (STB_LOCAL)
ffffffff81523fb0-ffffffff81524211: bio_integrity_prep (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
