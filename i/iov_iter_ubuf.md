# Function: <code>iov_iter_ubuf</code>

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
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147ae45)
Location: include/linux/uio.h:350
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
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
In fs/read_write.c (ffffffff814af9a6)
Location: include/linux/uio.h:372
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In io_uring/net.c (ffffffff817d79dc)
Location: include/linux/uio.h:372
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg
```
```
In lib/iov_iter.c (ffffffff818157d3)
Location: include/linux/uio.h:372
Inline: True
Inline callers:
  - lib/iov_iter.c:import_ubuf
  - lib/iov_iter.c:import_single_range
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
In fs/read_write.c (ffffffff814e1188)
Location: include/linux/uio.h:337
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In block/bio-integrity.c (ffffffff817f9401)
Location: include/linux/uio.h:337
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_map_user
```
```
In io_uring/net.c (ffffffff8181bd13)
Location: include/linux/uio.h:337
Inline: True
Inline callers:
  - io_uring/net.c:io_recvmsg
```
```
In lib/iov_iter.c (ffffffff81855d93)
Location: include/linux/uio.h:337
Inline: True
Inline callers:
  - lib/iov_iter.c:import_ubuf
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
