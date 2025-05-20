# Function: <code>iov_iter_is_kvec</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e3fcd)
Location: include/linux/uio.h:62
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8140fdb5)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8142968c)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814795ed)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (ffffffff81494310)
Location: include/linux/uio.h:63
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
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
In fs/fuse/file.c (ffffffff814991d0)
Location: include/linux/uio.h:66
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f0c5e)
Location: include/linux/uio.h:76
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:76
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff815804f2)
Location: include/linux/uio.h:78
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:78
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816262a7)
Location: include/linux/uio.h:92
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:92
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165e69e)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In lib/iov_iter.c (ffffffff81814696)
Location: include/linux/uio.h:119
Inline: True
Inline callers:
  - lib/iov_iter.c:iov_iter_extract_pages
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
In fs/fuse/file.c (ffffffff81698440)
Location: include/linux/uio.h:114
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
```
In lib/iov_iter.c (0)
Location: include/linux/uio.h:114
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/uio.h:114
Inline: True
```
```
In net/core/datagram.c (0)
Location: include/linux/uio.h:114
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050d64c)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c8edc)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c0000000006542dc)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000378480)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81421c6c)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814126ec)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141de0c)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81434b6c)
Location: include/linux/uio.h:64
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
```
</details>
</li>
</ul>

## Differences
