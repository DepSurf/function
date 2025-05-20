# Function: <code>bdev_write_inode</code>

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
In fs/block_dev.c (ffffffff81248650)
Location: fs/block_dev.c:53
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff81271085)
Location: fs/block_dev.c:66
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff812849f2)
Location: fs/block_dev.c:68
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff81291dc4)
Location: fs/block_dev.c:69
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff812b4b44)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff812dccda)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff812f213a)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff81313b7a)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff81326a8a)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bdev_write_inode(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360570)
Location: fs/block_dev.c:57
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
```
**Symbols:**

```
ffffffff81360570-ffffffff8136062f: bdev_write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bdev_write_inode(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136dae0)
Location: fs/block_dev.c:57
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
```
**Symbols:**

```
ffffffff8136dae0-ffffffff8136db9f: bdev_write_inode (STB_LOCAL)
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
In fs/block_dev.c (ffffffff81374577)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In block/bdev.c (ffffffff815c42c5)
Location: block/bdev.c:48
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
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
In block/bdev.c (ffffffff8166ebf5)
Location: block/bdev.c:48
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
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
In block/bdev.c (ffffffff81729ee2)
Location: block/bdev.c:49
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
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
In block/bdev.c (ffffffff81766252)
Location: block/bdev.c:49
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
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
In block/bdev.c (ffffffff817a7d12)
Location: block/bdev.c:52
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
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
In fs/block_dev.c (ffff8000103e18a8)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (c05b8b04)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (c0000000004e5658)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffe000297dee)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff8131f06a)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff8130fc0a)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff8131cb3a)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
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
In fs/block_dev.c (ffffffff8132dd3e)
Location: fs/block_dev.c:57
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
