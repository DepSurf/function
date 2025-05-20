# Function: <code>blkdev_get_no_open</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct block_device *blkdev_get_no_open(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e890)
Location: fs/block_dev.c:1359
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
**Symbols:**

```
ffffffff8136e890-ffffffff8136e9a3: blkdev_get_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct block_device *blkdev_get_no_open(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813751a0)
Location: fs/block_dev.c:1369
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
**Symbols:**

```
ffffffff813751a0-ffffffff81375264: blkdev_get_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct block_device *blkdev_get_no_open(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4b50)
Location: block/bdev.c:732
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
**Symbols:**

```
ffffffff815c4b50-ffffffff815c4c22: blkdev_get_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct block_device *blkdev_get_no_open(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bdev.c (0)
Location: block/bdev.c:737
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
**Symbols:**

```
ffffffff81e8b239-ffffffff81e8b24a: blkdev_get_no_open.cold (STB_LOCAL)
ffffffff8166f5b0-ffffffff8166f64f: blkdev_get_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct block_device *blkdev_get_no_open(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a970)
Location: block/bdev.c:736
Inline: False
Direct callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/blk-cgroup.c:blkcg_conf_open_bdev
```
**Symbols:**

```
ffffffff8172a970-ffffffff8172aa18: blkdev_get_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct block_device *blkdev_get_no_open(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81766bb0)
Location: block/bdev.c:719
Inline: False
Direct callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
**Symbols:**

```
ffffffff81766bb0-ffffffff81766c58: blkdev_get_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct block_device *blkdev_get_no_open(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a87f0)
Location: block/bdev.c:710
Inline: False
Direct callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:bdev_open_by_dev
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
**Symbols:**

```
ffffffff817a87f0-ffffffff817a8898: blkdev_get_no_open (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
