# Function: <code>queue_max_zone_append_sectors</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f6cf)
Location: include/linux/blkdev.h:1326
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_append_get_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155bed6)
Location: include/linux/blkdev.h:1424
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_append_get_pages
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
In block/bio.c (ffffffff8156454a)
Location: include/linux/blkdev.h:1409
Inline: True
Inline callers:
  - block/bio.c:bio_add_zone_append_page
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
In block/bio.c (ffffffff815c8a5d)
Location: include/linux/blkdev.h:1384
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:bio_add_zone_append_page
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
In block/bio.c (ffffffff81673b6c)
Location: include/linux/blkdev.h:1195
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
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
In block/bio.c (ffffffff8172f673)
Location: include/linux/blkdev.h:1143
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
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
In block/bio.c (ffffffff8176b94d)
Location: include/linux/blkdev.h:1124
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
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
In block/bio.c (ffffffff817ade00)
Location: include/linux/blkdev.h:1109
Inline: True
Inline callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_iov_bvec_set
  - block/bio.c:bio_add_zone_append_page
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
