# Function: <code>blkg_lookup_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d8e10)
Location: block/blk-cgroup.c:270
Inline: True
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff813d8e10-ffffffff813d8f48: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141eb80)
Location: block/blk-cgroup.c:270
Inline: True
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff8141eb80-ffffffff8141ecaf: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8143a140)
Location: block/blk-cgroup.c:271
Inline: True
Direct callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-cgroup.c:blkg_conf_prep
```
**Symbols:**

```
ffffffff8143a140-ffffffff8143a26f: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81447bb0)
Location: block/blk-cgroup.c:272
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff81447bb0-ffffffff81447ce5: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814747b0)
Location: block/blk-cgroup.c:272
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814747b0-ffffffff814748e5: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a8d50)
Location: block/blk-cgroup.c:272
Inline: False
Direct callers:
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff814a8d50-ffffffff814a8e62: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c2b70)
Location: block/blk-cgroup.c:356
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffffffff814c2b70-ffffffff814c2bff: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f1270)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffffffff814f1270-ffffffff814f130f: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8150a860)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffffffff8150a860-ffffffff8150a8fc: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156b7d0)
Location: block/blk-cgroup.c:380
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff8156b7d0-ffffffff8156b870: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586190)
Location: block/blk-cgroup.c:325
Inline: False
```
**Symbols:**

```
ffffffff81586190-ffffffff81586338: blkg_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158cbe2)
Location: block/blk-cgroup.c:323
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f2442)
Location: block/blk-cgroup.c:326
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a3c07)
Location: block/blk-cgroup.c:387
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81762937)
Location: block/blk-cgroup.c:396
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a15f4)
Location: block/blk-cgroup.c:471
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e5144)
Location: block/blk-cgroup.c:471
Inline: True
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
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060ddf8)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffff80001060ddf8-ffff80001060defc: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b88d4)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
c07b88d4-c07b8974: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007ab100)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
c0000000007ab100-c0000000007ab214: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe0004464b0)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffffffe0004464b0-ffffffe00044653e: blkg_lookup_create (STB_GLOBAL)
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
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81502e40)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffffffff81502e40-ffffffff81502edc: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f3320)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffffffff814f3320-ffffffff814f33bc: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814feed0)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffffffff814feed0-ffffffff814fef6c: blkg_lookup_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct blkcg_gq *blkg_lookup_create(struct blkcg *blkcg, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81518050)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffffffff81518050-ffffffff815180ec: blkg_lookup_create (STB_GLOBAL)
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
