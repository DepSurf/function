# Function: <code>bio_integrity_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bio_integrity_process(struct bio *bio, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff813e7560)
Location: block/bio-integrity.c:224
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_prep
  - block/bio-integrity.c:bio_integrity_verify_fn
```
**Symbols:**

```
ffffffff813e7560-ffffffff813e77f7: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bio_integrity_process(struct bio *bio, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8142d7e0)
Location: block/bio-integrity.c:224
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff8142d7e0-ffffffff8142da6d: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bio_integrity_process(struct bio *bio, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814475c0)
Location: block/bio-integrity.c:224
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814475c0-ffffffff81447843: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814559c0)
Location: block/bio-integrity.c:190
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814559c0-ffffffff81455bdf: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81481630)
Location: block/bio-integrity.c:190
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81481630-ffffffff8148183f: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814b60f0)
Location: block/bio-integrity.c:190
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814b60f0-ffffffff814b62fe: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814c99f0)
Location: block/bio-integrity.c:168
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814c99f0-ffffffff814c9bfe: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814f8090)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814f8090-ffffffff814f82bd: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81515e70)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81515e70-ffffffff8151609d: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81576810)
Location: block/bio-integrity.c:162
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81576810-ffffffff81576a19: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff815931e0)
Location: block/bio-integrity.c:162
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff815931e0-ffffffff815933ab: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81599fe0)
Location: block/bio-integrity.c:157
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81599fe0-ffffffff8159a1ad: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:156
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81602240-ffffffff81602403: bio_integrity_process (STB_LOCAL)
ffffffff81cd9fdb-ffffffff81cd9ffb: bio_integrity_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:156
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff816b4df0-ffffffff816b4fde: bio_integrity_process (STB_LOCAL)
ffffffff81e8dac2-ffffffff81e8dae2: bio_integrity_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:156
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff817748f0-ffffffff81774aef: bio_integrity_process (STB_LOCAL)
ffffffff82076ff3-ffffffff82077013: bio_integrity_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:168
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff817b4600-ffffffff817b4808: bio_integrity_process (STB_LOCAL)
ffffffff820f7049-ffffffff820f7069: bio_integrity_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio-integrity.c (0)
Location: block/bio-integrity.c:383
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff817f8440-ffffffff817f8648: bio_integrity_process (STB_LOCAL)
ffffffff821d483e-ffffffff821d485e: bio_integrity_process.cold (STB_LOCAL)
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
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffff80001061d278)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffff80001061d278-ffff80001061d4c8: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c07c4c7c)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
c07c4c7c-c07c4eb8: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (c0000000007bbcc0)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
c0000000007bbcc0-c0000000007bc000: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffe0004500fa)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffe0004500fa-ffffffe000450308: bio_integrity_process (STB_LOCAL)
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
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8150e450)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff8150e450-ffffffff8150e67d: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff814fe880)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff814fe880-ffffffff814feaad: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff8150a4e0)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff8150a4e0-ffffffff8150a70d: bio_integrity_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t bio_integrity_process(struct bio *bio, struct bvec_iter *proc_iter, integrity_processing_fn *proc_fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio-integrity.c (ffffffff81523b50)
Location: block/bio-integrity.c:153
Inline: False
Direct callers:
  - block/bio-integrity.c:bio_integrity_verify_fn
  - block/bio-integrity.c:bio_integrity_prep
```
**Symbols:**

```
ffffffff81523b50-ffffffff81523dad: bio_integrity_process (STB_LOCAL)
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
<b>Param added. </b>
<code>struct bvec_iter *proc_iter</code>
</li>
<li>
<b>Param reordered. </b>
<code>bio, proc_fn</code> ➡️ <code>bio, proc_iter, proc_fn</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
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
