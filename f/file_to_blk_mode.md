# Function: <code>file_to_blk_mode</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
blk_mode_t file_to_blk_mode(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff81768750)
Location: block/fops.c:474
Inline: False
Direct callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_open
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81768750-ffffffff81768793: file_to_blk_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
blk_mode_t file_to_blk_mode(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff817aa5e0)
Location: block/fops.c:569
Inline: False
Direct callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_open
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff817aa5e0-ffffffff817aa637: file_to_blk_mode (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
