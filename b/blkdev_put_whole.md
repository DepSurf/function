# Function: <code>blkdev_put_whole</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blkdev_put_whole(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c46d9)
Location: block/bdev.c:686
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put
```
**Symbols:**

```
ffffffff815c4370-ffffffff815c43b3: blkdev_put_whole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blkdev_put_whole(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166ecc0)
Location: block/bdev.c:691
Inline: False
Direct callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put
```
**Symbols:**

```
ffffffff8166ecc0-ffffffff8166ed0d: blkdev_put_whole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkdev_put_whole(struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81729f80)
Location: block/bdev.c:690
Inline: False
Direct callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put
```
**Symbols:**

```
ffffffff81729f80-ffffffff81729fcd: blkdev_put_whole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkdev_put_whole(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817662f0)
Location: block/bdev.c:675
Inline: False
Direct callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put
```
**Symbols:**

```
ffffffff817662f0-ffffffff8176632e: blkdev_put_whole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkdev_put_whole(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a7db0)
Location: block/bdev.c:666
Inline: False
Direct callers:
  - block/bdev.c:bdev_release
  - block/bdev.c:bdev_release
  - block/bdev.c:bdev_open_by_dev
```
**Symbols:**

```
ffffffff817a7db0-ffffffff817a7dee: blkdev_put_whole (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
