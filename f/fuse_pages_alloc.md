# Function: <code>fuse_pages_alloc</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81428357)
Location: fs/fuse/file.c:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
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
In fs/fuse/file.c (ffffffff81476005)
Location: fs/fuse/file.c:23
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
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
In fs/fuse/file.c (ffffffff81490a5e)
Location: fs/fuse/file.c:23
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149bf5f)
Location: fs/fuse/fuse_i.h:891
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
```
```
In fs/fuse/ioctl.c (ffffffff814a171e)
Location: fs/fuse/fuse_i.h:891
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff814f3a5b)
Location: fs/fuse/fuse_i.h:896
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
```
```
In fs/fuse/ioctl.c (ffffffff814f97e5)
Location: fs/fuse/fuse_i.h:896
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff8157cf4d)
Location: fs/fuse/fuse_i.h:917
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
```
```
In fs/fuse/ioctl.c (ffffffff81589b7e)
Location: fs/fuse/fuse_i.h:917
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff81622e0d)
Location: fs/fuse/fuse_i.h:920
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
```
```
In fs/fuse/ioctl.c (ffffffff816301e9)
Location: fs/fuse/fuse_i.h:920
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff8165b256)
Location: fs/fuse/fuse_i.h:925
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
```
```
In fs/fuse/ioctl.c (ffffffff81668275)
Location: fs/fuse/fuse_i.h:925
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffffffff81694f26)
Location: fs/fuse/fuse_i.h:952
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_pages_realloc
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
```
```
In fs/fuse/ioctl.c (ffffffff816a2575)
Location: fs/fuse/fuse_i.h:952
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
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
In fs/fuse/file.c (ffff80001050a838)
Location: fs/fuse/file.c:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
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
In fs/fuse/file.c (c06c7b34)
Location: fs/fuse/file.c:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
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
In fs/fuse/file.c (c000000000652a64)
Location: fs/fuse/file.c:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
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
In fs/fuse/file.c (ffffffe000376fd6)
Location: fs/fuse/file.c:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
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
In fs/fuse/file.c (ffffffff81420937)
Location: fs/fuse/file.c:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
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
In fs/fuse/file.c (ffffffff814113b7)
Location: fs/fuse/file.c:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
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
In fs/fuse/file.c (ffffffff8141cad7)
Location: fs/fuse/file.c:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
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
In fs/fuse/file.c (ffffffff814338b7)
Location: fs/fuse/file.c:22
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_io_alloc
```
</details>
</li>
</ul>

## Differences
