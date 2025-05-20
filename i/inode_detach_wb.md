# Function: <code>inode_detach_wb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227b3a)
Location: include/linux/writeback.h:224
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff812486cd)
Location: include/linux/writeback.h:224
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8125026a)
Location: include/linux/writeback.h:224
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff81271104)
Location: include/linux/writeback.h:224
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126330a)
Location: include/linux/writeback.h:237
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff81284a71)
Location: include/linux/writeback.h:237
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270b2a)
Location: include/linux/writeback.h:237
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff8129278e)
Location: include/linux/writeback.h:237
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8129345a)
Location: include/linux/writeback.h:216
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff812b559e)
Location: include/linux/writeback.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b908a)
Location: include/linux/writeback.h:216
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff812dcaae)
Location: include/linux/writeback.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ce1ca)
Location: include/linux/writeback.h:216
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff812f202e)
Location: include/linux/writeback.h:216
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eb08a)
Location: include/linux/writeback.h:243
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff813139ce)
Location: include/linux/writeback.h:243
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffff812fcbca)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff813268de)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffff8133543a)
Location: include/linux/writeback.h:246
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff81360e0e)
Location: include/linux/writeback.h:246
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffff81340daa)
Location: include/linux/writeback.h:246
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff8136d0f9)
Location: include/linux/writeback.h:246
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffff8134719a)
Location: include/linux/writeback.h:246
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff81373969)
Location: include/linux/writeback.h:246
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffff81394bfa)
Location: include/linux/writeback.h:247
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
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
In fs/inode.c (ffffffff81416f9c)
Location: include/linux/writeback.h:251
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
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
In fs/inode.c (ffffffff814a259c)
Location: include/linux/writeback.h:243
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
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
In fs/inode.c (ffffffff814d76fc)
Location: include/linux/writeback.h:238
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
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
In fs/inode.c (ffffffff81509a0c)
Location: include/linux/writeback.h:237
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
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
In fs/inode.c (ffff8000103acd94)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffff8000103e13bc)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (c058dc64)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (c05b98e8)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (c0000000004a8564)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (c0000000004e7398)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffe000271bba)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffe000297c02)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffff812f51aa)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff8131eebe)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffff812e5dca)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff8130fa5e)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffff812f2fba)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff8131c98e)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
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
In fs/inode.c (ffffffff813048ea)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
```
```
In fs/block_dev.c (ffffffff8132ea6c)
Location: include/linux/writeback.h:245
Inline: True
Inline callers:
  - fs/block_dev.c:bdev_evict_inode
```
</details>
</li>
</ul>

## Differences
