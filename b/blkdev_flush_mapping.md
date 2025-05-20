# Function: <code>blkdev_flush_mapping</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void blkdev_flush_mapping(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4250)
Location: block/bdev.c:654
Inline: False
Direct callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put
```
**Symbols:**

```
ffffffff815c4250-ffffffff815c4361: blkdev_flush_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blkdev_flush_mapping(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166eb80)
Location: block/bdev.c:659
Inline: False
Direct callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put_whole
```
**Symbols:**

```
ffffffff8166eb80-ffffffff8166ecbd: blkdev_flush_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkdev_flush_mapping(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81729e80)
Location: block/bdev.c:658
Inline: False
Direct callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put_whole
```
**Symbols:**

```
ffffffff81729e80-ffffffff81729f63: blkdev_flush_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkdev_flush_mapping(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817661f0)
Location: block/bdev.c:643
Inline: False
Direct callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_put_whole
```
**Symbols:**

```
ffffffff817661f0-ffffffff817662d3: blkdev_flush_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkdev_flush_mapping(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a7cb0)
Location: block/bdev.c:634
Inline: False
Direct callers:
  - block/bdev.c:bdev_release
  - block/bdev.c:blkdev_put_whole
```
**Symbols:**

```
ffffffff817a7cb0-ffffffff817a7d93: blkdev_flush_mapping (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
