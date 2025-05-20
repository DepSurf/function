# Function: <code>blkdev_put_no_open</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blkdev_put_no_open(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136dfa3)
Location: fs/block_dev.c:1394
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_put
Direct callers:
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8136ec80-ffffffff8136ecbc: blkdev_put_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blkdev_put_no_open(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374963)
Location: fs/block_dev.c:1397
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_put
Direct callers:
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff813755f0-ffffffff8137562c: blkdev_put_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blkdev_put_no_open(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4673)
Location: block/bdev.c:762
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
Direct callers:
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff815c5070-ffffffff815c50a0: blkdev_put_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blkdev_put_no_open(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166ed95)
Location: block/bdev.c:761
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
Direct callers:
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8166fb00-ffffffff8166fb1a: blkdev_put_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blkdev_put_no_open(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172b116)
Location: block/bdev.c:760
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:blkdev_put
Direct callers:
  - block/blk-cgroup.c:blkg_conf_finish
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkcg_conf_open_bdev
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8172af10-ffffffff8172af2a: blkdev_put_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blkdev_put_no_open(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81767383)
Location: block/bdev.c:743
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:blkdev_put
Direct callers:
  - block/blk-cgroup.c:blkg_conf_exit
  - block/blk-cgroup.c:blkg_conf_open_bdev
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
**Symbols:**

```
ffffffff81767180-ffffffff8176719d: blkdev_put_no_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blkdev_put_no_open(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a9053)
Location: block/bdev.c:734
Inline: True
Inline callers:
  - block/bdev.c:bdev_statx_dioalign
  - block/bdev.c:bdev_release
  - block/bdev.c:bdev_open_by_dev
Direct callers:
  - block/blk-cgroup.c:blkg_conf_exit
  - block/blk-cgroup.c:blkg_conf_open_bdev
  - block/blk-cgroup.c:blkg_conf_open_bdev
```
**Symbols:**

```
ffffffff817a8e50-ffffffff817a8e6d: blkdev_put_no_open (STB_GLOBAL)
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
