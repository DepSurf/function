# Function: <code>bio_integrity_clone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff813e7470)
Location: block/bio-integrity.c:459
Inline: True
Direct callers:
  - block/bio.c:bio_clone_fast
  - block/bio.c:bio_clone_bioset
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff813e7470-ffffffff813e74e8: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8142d6f0)
Location: block/bio-integrity.c:459
Inline: True
Direct callers:
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8142d6f0-ffffffff8142d769: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814474d0)
Location: block/bio-integrity.c:459
Inline: True
Direct callers:
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814474d0-ffffffff81447549: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814557b0)
Location: block/bio-integrity.c:447
Inline: False
Direct callers:
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814557b0-ffffffff81455829: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81481430)
Location: block/bio-integrity.c:445
Inline: False
Direct callers:
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81481430-ffffffff814814a9: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814b6040)
Location: block/bio-integrity.c:444
Inline: False
Direct callers:
  - block/bio.c:bio_clone_bioset
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814b6040-ffffffff814b60b9: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814c98f0)
Location: block/bio-integrity.c:417
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - block/bounce.c:blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814c98f0-ffffffff814c9969: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814f84a0)
Location: block/bio-integrity.c:406
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814f84a0-ffffffff814f851d: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81516220)
Location: block/bio-integrity.c:406
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81516220-ffffffff8151629d: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81576710)
Location: block/bio-integrity.c:414
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff81576710-ffffffff8157678d: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81593630)
Location: block/bio-integrity.c:414
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:clone_bio
```
**Symbols:**

```
ffffffff81593630-ffffffff815936ad: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8159a410)
Location: block/bio-integrity.c:408
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8159a410-ffffffff8159a489: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81602570)
Location: block/bio-integrity.c:403
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81602570-ffffffff816025e9: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff816b57f0)
Location: block/bio-integrity.c:404
Inline: False
Direct callers:
  - block/bio.c:__bio_clone
```
**Symbols:**

```
ffffffff816b57f0-ffffffff816b5872: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81775400)
Location: block/bio-integrity.c:404
Inline: False
Direct callers:
  - block/bio.c:__bio_clone
```
**Symbols:**

```
ffffffff81775400-ffffffff8177548f: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff817b5100)
Location: block/bio-integrity.c:416
Inline: False
Direct callers:
  - block/bio.c:__bio_clone
```
**Symbols:**

```
ffffffff817b5100-ffffffff817b518f: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff817f9b10)
Location: block/bio-integrity.c:614
Inline: False
Direct callers:
  - block/bio.c:__bio_clone
```
**Symbols:**

```
ffffffff817f9b10-ffffffff817f9b9f: bio_integrity_clone (STB_GLOBAL)
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
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffff80001061d140)
Location: block/bio-integrity.c:406
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffff80001061d140-ffff80001061d1d4: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c07c502c)
Location: block/bio-integrity.c:406
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
c07c502c-c07c50c0: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c0000000007bc1d0)
Location: block/bio-integrity.c:406
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
c0000000007bc1d0-c0000000007bc29c: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffe00044fff0)
Location: block/bio-integrity.c:406
Inline: True
Direct callers:
  - block/bio.c:bio_clone_fast
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffe00044fff0-ffffffe00045007e: bio_integrity_clone (STB_GLOBAL)
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
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8150e800)
Location: block/bio-integrity.c:406
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8150e800-ffffffff8150e87d: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814fec30)
Location: block/bio-integrity.c:406
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff814fec30-ffffffff814fecad: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8150a890)
Location: block/bio-integrity.c:406
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff8150a890-ffffffff8150a90d: bio_integrity_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bio_integrity_clone(struct bio *bio, struct bio *bio_src, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81523f30)
Location: block/bio-integrity.c:406
Inline: False
Direct callers:
  - block/bio.c:bio_clone_fast
  - block/bounce.c:__blk_queue_bounce
  - drivers/md/dm.c:__split_and_process_non_flush
```
**Symbols:**

```
ffffffff81523f30-ffffffff81523fad: bio_integrity_clone (STB_GLOBAL)
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
