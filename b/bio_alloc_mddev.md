# Function: <code>bio_alloc_mddev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81690d50)
Location: drivers/md/md.c:164
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_super_write
```
**Symbols:**

```
ffffffff81690d50-ffffffff81690d7f: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f1a70)
Location: drivers/md/md.c:165
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:md_super_write
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff816f1a70-ffffffff816f1a9f: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81723320)
Location: drivers/md/md.c:178
Inline: True
Direct callers:
  - drivers/md/md.c:sync_page_io
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81723320-ffffffff8172334f: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8173a750)
Location: drivers/md/md.c:191
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff8173a750-ffffffff8173a77f: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817acd70)
Location: drivers/md/md.c:191
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff817acd70-ffffffff817acd9f: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f2e80)
Location: drivers/md/md.c:211
Inline: True
Direct callers:
  - drivers/md/md.c:md_flush_request
```
**Symbols:**

```
ffffffff817f2e80-ffffffff817f2eb4: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8181ee60)
Location: drivers/md/md.c:207
Inline: True
Direct callers:
  - drivers/md/md.c:md_flush_request
```
**Symbols:**

```
ffffffff8181ee60-ffffffff8181ee94: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818612d0)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff818612d0-ffffffff81861304: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81892f00)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81892f00-ffffffff81892f34: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81965638)
Location: drivers/md/md.c:347
Inline: True
Inline callers:
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff819615d0-ffffffff81961604: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196c090)
Location: drivers/md/md.c:343
Inline: True
Inline callers:
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81967f00-ffffffff81967f34: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae4548)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffff800010ae4548-ffff800010ae45bc: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc7ba8)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
c0bc7ba8-c0bc7bfc: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd0390)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
c000000000bd0390-c000000000bd0414: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006db762)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffe0006db762-ffffffe0006db7ca: bio_alloc_mddev (STB_GLOBAL)
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
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81838d80)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff81838d80-ffffffff81838db4: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818003f0)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff818003f0-ffffffff81800424: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818883b0)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff818883b0-ffffffff818883e4: bio_alloc_mddev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_mddev(gfp_t gfp_mask, int nr_iovecs, struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a5950)
Location: drivers/md/md.c:253
Inline: True
Direct callers:
  - drivers/md/md.c:submit_flushes
```
**Symbols:**

```
ffffffff818a5950-ffffffff818a5984: bio_alloc_mddev (STB_GLOBAL)
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
