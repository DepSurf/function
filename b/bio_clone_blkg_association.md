# Function: <code>bio_clone_blkg_association</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498260)
Location: block/bio.c:2098
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff814981c0-ffffffff814981de: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c60dd)
Location: block/bio.c:2132
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
Direct callers:
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff814c6040-ffffffff814c605e: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de4e0)
Location: block/bio.c:2174
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
Direct callers:
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff814de440-ffffffff814de45e: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153e000)
Location: block/bio.c:1753
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
**Symbols:**

```
ffffffff8153da00-ffffffff8153da1a: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81585a30)
Location: block/blk-cgroup.c:1884
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/bio.c:__bio_clone_fast
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
**Symbols:**

```
ffffffff81585a30-ffffffff81585ab3: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158c400)
Location: block/blk-cgroup.c:1893
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/bio.c:__bio_clone_fast
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff8158c400-ffffffff8158c483: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f1a30)
Location: block/blk-cgroup.c:1887
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/bio.c:__bio_clone_fast
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff815f1a30-ffffffff815f1ab3: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a3ec0)
Location: block/blk-cgroup.c:1975
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/bio.c:__bio_clone
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff816a3ec0-ffffffff816a3ef7: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81762c10)
Location: block/blk-cgroup.c:1981
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/bio.c:__bio_clone
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff81762c10-ffffffff81762c47: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a18e0)
Location: block/blk-cgroup.c:2072
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/bio.c:__bio_clone
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff817a18e0-ffffffff817a1917: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e5420)
Location: block/blk-cgroup.c:2088
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - block/bio.c:__bio_clone
  - block/blk-crypto-fallback.c:blk_crypto_fallback_clone_bio
  - drivers/md/md.c:md_submit_discard_bio
```
**Symbols:**

```
ffffffff817e5420-ffffffff817e5457: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105db93c)
Location: block/bio.c:2174
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffff8000105db878-ffff8000105db8b0: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c07884e0)
Location: block/bio.c:2174
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
Direct callers:
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
c0788428-c0788450: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076b87c)
Location: block/bio.c:2174
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
c00000000076b780-c00000000076b7c4: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e55c)
Location: block/bio.c:2174
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffe00041e4b2-ffffffe00041e4e8: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6ac0)
Location: block/bio.c:2174
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
Direct callers:
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff814d6a20-ffffffff814d6a3e: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7480)
Location: block/bio.c:2174
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
Direct callers:
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff814c73e0-ffffffff814c73fe: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2b50)
Location: block/bio.c:2174
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
Direct callers:
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff814d2ab0-ffffffff814d2ace: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_clone_blkg_association(struct bio *dst, struct bio *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb620)
Location: block/bio.c:2174
Inline: False
Direct callers:
  - block/bio.c:__bio_clone_fast
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff814eb620-ffffffff814eb654: bio_clone_blkg_association (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
