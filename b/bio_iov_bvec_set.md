# Function: <code>bio_iov_bvec_set</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815648e1)
Location: block/bio.c:964
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
In block/bio.c (ffffffff815c8ce4)
Location: block/bio.c:1047
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bio_iov_bvec_set(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816739a0)
Location: block/bio.c:1133
Inline: False
Direct callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/bio.c:bio_iov_iter_get_pages
```
**Symbols:**

```
ffffffff816739a0-ffffffff81673a18: bio_iov_bvec_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bio_iov_bvec_set(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172f940)
Location: block/bio.c:1185
Inline: False
Direct callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8172f940-ffffffff8172f9b8: bio_iov_bvec_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bio_iov_bvec_set(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176bb60)
Location: block/bio.c:1161
Inline: False
Direct callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff8176bb60-ffffffff8176bbd5: bio_iov_bvec_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bio_iov_bvec_set(struct bio *bio, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ae000)
Location: block/bio.c:1171
Inline: False
Direct callers:
  - block/fops.c:__blkdev_direct_IO_async
  - block/bio.c:bio_iov_iter_get_pages
  - block/blk-map.c:blk_rq_map_user_iov
```
**Symbols:**

```
ffffffff817ae000-ffffffff817ae075: bio_iov_bvec_set (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
