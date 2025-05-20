# Function: <code>fuse_sync_writes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81317a7d)
Location: fs/fuse/file.c:391
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_flush
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_file_fallocate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134d61a)
Location: fs/fuse/file.c:391
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81362f2a)
Location: fs/fuse/file.c:392
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813778bb)
Location: fs/fuse/file.c:387
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139c65b)
Location: fs/fuse/file.c:387
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813cb9ea)
Location: fs/fuse/file.c:387
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync_common
  - fs/fuse/file.c:fuse_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e52c0)
Location: fs/fuse/file.c:391
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff81410226)
Location: fs/fuse/file.c:403
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff81429bec)
Location: fs/fuse/file.c:430
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff8147aa33)
Location: fs/fuse/file.c:437
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff814956bf)
Location: fs/fuse/file.c:460
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff8149a71f)
Location: fs/fuse/file.c:464
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff814f2170)
Location: fs/fuse/file.c:468
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff81581afb)
Location: fs/fuse/file.c:474
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff8162797b)
Location: fs/fuse/file.c:474
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff8165fd51)
Location: fs/fuse/file.c:475
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff81699bb1)
Location: fs/fuse/file.c:476
Inline: True
Inline callers:
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffff80001050db6c)
Location: fs/fuse/file.c:430
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (c06c93fc)
Location: fs/fuse/file.c:430
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (c000000000654614)
Location: fs/fuse/file.c:430
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffe000378914)
Location: fs/fuse/file.c:430
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff814221cc)
Location: fs/fuse/file.c:430
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff81412c4c)
Location: fs/fuse/file.c:430
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff8141e36c)
Location: fs/fuse/file.c:430
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
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
In fs/fuse/file.c (ffffffff814350cc)
Location: fs/fuse/file.c:430
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_fsync
  - fs/fuse/file.c:fuse_flush
```
</details>
</li>
</ul>

## Differences
