# Function: <code>bio_clone_bioset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bio *bio_clone_bioset(struct bio *bio_src, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b1c40)
Location: block/bio.c:632
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/block/xen-blkfront.c:blkif_recover
```
**Symbols:**

```
ffffffff813b1c40-ffffffff813b1f30: bio_clone_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bio *bio_clone_bioset(struct bio *bio_src, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f6830)
Location: block/bio.c:633
Inline: False
Direct callers:
  - block/bio.c:bio_split
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff813f6830-ffffffff813f6b85: bio_clone_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bio *bio_clone_bioset(struct bio *bio_src, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81410290)
Location: block/bio.c:637
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81410290-ffffffff81410630: bio_clone_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bio *bio_clone_bioset(struct bio *bio_src, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141dcd0)
Location: block/bio.c:652
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff8141dcd0-ffffffff8141dfeb: bio_clone_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio *bio_clone_bioset(struct bio *bio_src, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81447760)
Location: block/bio.c:655
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff81447760-ffffffff81447a7b: bio_clone_bioset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bio *bio_clone_bioset(struct bio *bio_src, gfp_t gfp_mask, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147a870)
Location: block/bio.c:656
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff8147a870-ffffffff8147ab72: bio_clone_bioset (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
</ul>
