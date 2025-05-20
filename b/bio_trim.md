# Function: <code>bio_trim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b0950)
Location: block/bio.c:1822
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_recover
```
**Symbols:**

```
ffffffff813b0950-ffffffff813b0983: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f4060)
Location: block/bio.c:1817
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff813f4060-ffffffff813f4094: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140da10)
Location: block/bio.c:1864
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff8140da10-ffffffff8140da44: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141c530)
Location: block/bio.c:1889
Inline: True
```
**Symbols:**

```
ffffffff8141c530-ffffffff8141c579: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814470f0)
Location: block/bio.c:1853
Inline: True
```
**Symbols:**

```
ffffffff814470f0-ffffffff81447139: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479d00)
Location: block/bio.c:1911
Inline: True
```
**Symbols:**

```
ffffffff81479d00-ffffffff81479d49: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814976e0)
Location: block/bio.c:1843
Inline: True
```
**Symbols:**

```
ffffffff814976e0-ffffffff81497729: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c50a0)
Location: block/bio.c:1880
Inline: True
```
**Symbols:**

```
ffffffff814c50a0-ffffffff814c50ea: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ddfa0)
Location: block/bio.c:1922
Inline: True
```
**Symbols:**

```
ffffffff814ddfa0-ffffffff814ddfea: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153db60)
Location: block/bio.c:1501
Inline: True
```
**Symbols:**

```
ffffffff8153db60-ffffffff8153dbaa: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a6e0)
Location: block/bio.c:1504
Inline: True
```
**Symbols:**

```
ffffffff8155a6e0-ffffffff8155a72a: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562eb0)
Location: block/bio.c:1467
Inline: True
```
**Symbols:**

```
ffffffff81562eb0-ffffffff81562efa: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bio_trim(struct bio *bio, sector_t offset, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6b30)
Location: block/bio.c:1552
Inline: False
```
**Symbols:**

```
ffffffff815c6b30-ffffffff815c6b9e: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_trim(struct bio *bio, sector_t offset, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81671a40)
Location: block/bio.c:1610
Inline: False
```
**Symbols:**

```
ffffffff81671a40-ffffffff81671ad7: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_trim(struct bio *bio, sector_t offset, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172d2e0)
Location: block/bio.c:1673
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
**Symbols:**

```
ffffffff8172d2e0-ffffffff8172d377: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_trim(struct bio *bio, sector_t offset, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81769690)
Location: block/bio.c:1658
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
**Symbols:**

```
ffffffff81769690-ffffffff81769727: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_trim(struct bio *bio, sector_t offset, sector_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ab710)
Location: block/bio.c:1665
Inline: False
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
**Symbols:**

```
ffffffff817ab710-ffffffff817ab7a7: bio_trim (STB_GLOBAL)
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
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105da618)
Location: block/bio.c:1922
Inline: True
```
**Symbols:**

```
ffff8000105da618-ffff8000105da684: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787e50)
Location: block/bio.c:1922
Inline: True
```
**Symbols:**

```
c0787e50-c0787eb4: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076b4c0)
Location: block/bio.c:1922
Inline: True
```
**Symbols:**

```
c00000000076b4c0-c00000000076b568: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e36a)
Location: block/bio.c:1922
Inline: True
```
**Symbols:**

```
ffffffe00041e36a-ffffffe00041e3d0: bio_trim (STB_GLOBAL)
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
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6580)
Location: block/bio.c:1922
Inline: True
```
**Symbols:**

```
ffffffff814d6580-ffffffff814d65ca: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6f40)
Location: block/bio.c:1922
Inline: True
```
**Symbols:**

```
ffffffff814c6f40-ffffffff814c6f8a: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2610)
Location: block/bio.c:1922
Inline: True
```
**Symbols:**

```
ffffffff814d2610-ffffffff814d265a: bio_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bio_trim(struct bio *bio, int offset, int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb130)
Location: block/bio.c:1922
Inline: True
```
**Symbols:**

```
ffffffff814eb130-ffffffff814eb17a: bio_trim (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int offset</code> ➡️ <code>sector_t offset</code>
</li>
<li>
<b>Param type changed. </b>
<code>int size</code> ➡️ <code>sector_t size</code>
</li>
</ul>
</details>
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
