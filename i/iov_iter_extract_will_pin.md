# Function: <code>iov_iter_extract_will_pin</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81511a8e)
Location: include/linux/uio.h:411
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In block/bio.c (ffffffff8176bc13)
Location: include/linux/uio.h:411
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff817784f8)
Location: include/linux/uio.h:411
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/direct-io.c (ffffffff81545f39)
Location: include/linux/uio.h:374
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In block/bio.c (ffffffff817ae0b2)
Location: include/linux/uio.h:374
Inline: True
Inline callers:
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-map.c (ffffffff817ba8d4)
Location: include/linux/uio.h:374
Inline: True
Inline callers:
  - block/blk-map.c:bio_map_user_iov
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
