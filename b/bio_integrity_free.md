# Function: <code>bio_integrity_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff813e7100)
Location: block/bio-integrity.c:103
Inline: False
Direct callers:
  - block/bio.c:__bio_free
```
**Symbols:**

```
ffffffff813e7100-ffffffff813e71b7: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8142d390)
Location: block/bio-integrity.c:105
Inline: False
Direct callers:
  - block/bio.c:__bio_free
```
**Symbols:**

```
ffffffff8142d390-ffffffff8142d439: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81447170)
Location: block/bio-integrity.c:105
Inline: False
Direct callers:
  - block/bio.c:__bio_free
```
**Symbols:**

```
ffffffff81447170-ffffffff81447216: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81455700)
Location: block/bio-integrity.c:105
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff81455700-ffffffff814557a4: bio_integrity_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81481380)
Location: block/bio-integrity.c:105
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff81481380-ffffffff81481424: bio_integrity_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814b5f90)
Location: block/bio-integrity.c:105
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff814b5f90-ffffffff814b603d: bio_integrity_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814c9840)
Location: block/bio-integrity.c:105
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff814c9840-ffffffff814c98ed: bio_integrity_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814f7f60)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff814f7f60-ffffffff814f8009: bio_integrity_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81516530)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff81516530-ffffffff815165dc: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81576cb0)
Location: block/bio-integrity.c:106
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff81576cb0-ffffffff81576d64: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff815939c0)
Location: block/bio-integrity.c:106
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff815939c0-ffffffff81593a74: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8159a7a0)
Location: block/bio-integrity.c:101
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff8159a7a0-ffffffff8159a854: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81602980)
Location: block/bio-integrity.c:101
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff81602980-ffffffff81602a34: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff816b54e0)
Location: block/bio-integrity.c:101
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff816b54e0-ffffffff816b55a0: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff817750b0)
Location: block/bio-integrity.c:101
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff817750b0-ffffffff81775170: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff817b4dd0)
Location: block/bio-integrity.c:101
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff817b4dd0-ffffffff817b4e90: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff817f8e70)
Location: block/bio-integrity.c:142
Inline: False
Direct callers:
  - block/bio.c:bio_uninit
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_copy_user
```
**Symbols:**

```
ffffffff817f8e70-ffffffff817f90b2: bio_integrity_free (STB_GLOBAL)
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
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffff80001061d788)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffff80001061d788-ffff80001061d860: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c07c5370)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
c07c5370-c07c5418: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c0000000007bc680)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
c0000000007bc680-c0000000007bc7cc: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffe00045056e)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffe00045056e-ffffffe000450624: bio_integrity_free (STB_GLOBAL)
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
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8150eb10)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff8150eb10-ffffffff8150ebbc: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814fef40)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff814fef40-ffffffff814fefec: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8150aba0)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff8150aba0-ffffffff8150ac4c: bio_integrity_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_integrity_free(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81524240)
Location: block/bio-integrity.c:90
Inline: False
Direct callers:
  - block/bio-integrity.c:__bio_integrity_endio
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff81524240-ffffffff815242ec: bio_integrity_free (STB_GLOBAL)
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
