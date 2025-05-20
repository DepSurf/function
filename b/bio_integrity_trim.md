# Function: <code>bio_integrity_trim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio, unsigned int offset, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff813e7360)
Location: block/bio-integrity.c:440
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff813e7360-ffffffff813e73ce: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio, unsigned int offset, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8142d5e0)
Location: block/bio-integrity.c:440
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8142d5e0-ffffffff8142d64e: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio, unsigned int offset, unsigned int sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814473c0)
Location: block/bio-integrity.c:440
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814473c0-ffffffff8144742e: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814554b0)
Location: block/bio-integrity.c:430
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814554b0-ffffffff81455505: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81481140)
Location: block/bio-integrity.c:428
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81481140-ffffffff8148118e: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814b5d30)
Location: block/bio-integrity.c:427
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814b5d30-ffffffff814b5d83: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814c95f0)
Location: block/bio-integrity.c:400
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814c95f0-ffffffff814c9643: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814f7e70)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814f7e70-ffffffff814f7ec3: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81515d00)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81515d00-ffffffff81515d53: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81576440)
Location: block/bio-integrity.c:397
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff81576440-ffffffff81576493: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff815933b0)
Location: block/bio-integrity.c:397
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff815933b0-ffffffff81593400: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8159a1b0)
Location: block/bio-integrity.c:391
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8159a1b0-ffffffff8159a207: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:386
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81cda05d-ffffffff81cda07c: bio_integrity_trim.cold (STB_LOCAL)
ffffffff816028e0-ffffffff81602958: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:387
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - drivers/md/dm.c:alloc_tio
```
**Symbols:**

```
ffffffff81e8db43-ffffffff81e8db62: bio_integrity_trim.cold (STB_LOCAL)
ffffffff816b5430-ffffffff816b54b6: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:387
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - drivers/md/dm.c:alloc_tio
```
**Symbols:**

```
ffffffff82077033-ffffffff82077052: bio_integrity_trim.cold (STB_LOCAL)
ffffffff81774fe0-ffffffff81775066: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:399
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - drivers/md/dm.c:alloc_tio
```
**Symbols:**

```
ffffffff820f7089-ffffffff820f70a8: bio_integrity_trim.cold (STB_LOCAL)
ffffffff817b4d00-ffffffff817b4d83: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:597
Inline: False
Direct callers:
  - block/bio.c:bio_trim
  - block/bio.c:bio_split
  - drivers/md/dm.c:alloc_tio
```
**Symbols:**

```
ffffffff821d487e-ffffffff821d489d: bio_integrity_trim.cold (STB_LOCAL)
ffffffff817f8da0-ffffffff817f8e23: bio_integrity_trim (STB_GLOBAL)
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
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffff80001061ce58)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffff80001061ce58-ffff80001061cec4: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c07c4acc)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
c07c4acc-c07c4b28: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c0000000007bba90)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
c0000000007bba90-c0000000007bbaec: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffe00044fd42)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffe00044fd42-ffffffe00044fda2: bio_integrity_trim (STB_GLOBAL)
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
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8150e2e0)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8150e2e0-ffffffff8150e333: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814fe710)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814fe710-ffffffff814fe763: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8150a370)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8150a370-ffffffff8150a3c3: bio_integrity_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_integrity_trim(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff815239e0)
Location: block/bio-integrity.c:389
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff815239e0-ffffffff81523a33: bio_integrity_trim (STB_GLOBAL)
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
<b>Param removed. </b>
<code>unsigned int offset</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int sectors</code>
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
