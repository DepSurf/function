# Function: <code>blk_queue_depth</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8144ae26)
Location: include/linux/blkdev.h:800
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-wbt.c (ffffffff814590a9)
Location: include/linux/blkdev.h:844
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-wbt.c (ffffffff81484dfb)
Location: include/linux/blkdev.h:864
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-wbt.c (ffffffff814b9cdf)
Location: include/linux/blkdev.h:878
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-wbt.c (ffffffff814cde26)
Location: include/linux/blkdev.h:743
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-wbt.c (ffffffff814fc6db)
Location: include/linux/blkdev.h:755
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81510601)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (ffffffff8151a630)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81571bee)
Location: include/linux/blkdev.h:788
Inline: True
```
```
In block/blk-wbt.c (ffffffff8157ad7d)
Location: include/linux/blkdev.h:788
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158ce3e)
Location: include/linux/blkdev.h:837
Inline: True
```
```
In block/blk-wbt.c (ffffffff81597130)
Location: include/linux/blkdev.h:837
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
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
In block/blk-iocost.c (ffffffff81593b8e)
Location: include/linux/blkdev.h:839
Inline: True
```
```
In block/blk-wbt.c (ffffffff8159def0)
Location: include/linux/blkdev.h:839
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
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
In block/blk-iocost.c (ffffffff815fb01d)
Location: include/linux/blkdev.h:805
Inline: True
```
```
In block/blk-wbt.c (ffffffff816065d3)
Location: include/linux/blkdev.h:805
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
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
In block/blk-iocost.c (ffffffff816ae03d)
Location: include/linux/blkdev.h:741
Inline: True
```
```
In block/blk-wbt.c (ffffffff816ba343)
Location: include/linux/blkdev.h:741
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
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
In block/blk-iocost.c (ffffffff8176cd0d)
Location: include/linux/blkdev.h:729
Inline: True
```
```
In block/blk-wbt.c (ffffffff8177a8c3)
Location: include/linux/blkdev.h:729
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_queue_depth_changed
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
In block/blk-iocost.c (ffffffff817ac7b4)
Location: include/linux/blkdev.h:713
Inline: True
```
```
In block/blk-wbt.c (ffffffff817bb09c)
Location: include/linux/blkdev.h:713
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_queue_depth_changed
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
In block/blk-iocost.c (ffffffff817f0581)
Location: include/linux/blkdev.h:690
Inline: True
```
```
In block/blk-wbt.c (ffffffff817ff7d3)
Location: include/linux/blkdev.h:690
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-wbt.c:wbt_queue_depth_changed
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010614058)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (ffff8000106224e8)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07beb48)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (c07ca0a8)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b34ac)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (c0000000007c25c0)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044b7cc)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (ffffffe0004544da)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508be1)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (ffffffff81512c10)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f9091)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (ffffffff81502f30)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81504c71)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (ffffffff8150eca0)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151e291)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In block/blk-wbt.c (ffffffff81528470)
Location: include/linux/blkdev.h:772
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
</ul>

## Differences
