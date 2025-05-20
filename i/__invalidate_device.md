# Function: <code>__invalidate_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81248040)
Location: fs/block_dev.c:1810
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff81248040-ffffffff81248099: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270830)
Location: fs/block_dev.c:1889
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff81270830-ffffffff81270889: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812841b0)
Location: fs/block_dev.c:2211
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff812841b0-ffffffff81284209: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81291860)
Location: fs/block_dev.c:2127
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff81291860-ffffffff812918b9: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b45c0)
Location: fs/block_dev.c:2123
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff812b45c0-ffffffff812b4619: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dbbe0)
Location: fs/block_dev.c:2139
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff812dbbe0-ffffffff812dbc39: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f12d0)
Location: fs/block_dev.c:2173
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff812f12d0-ffffffff812f1329: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81313180)
Location: fs/block_dev.c:2214
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff81313180-ffffffff813131d7: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813260c0)
Location: fs/block_dev.c:2191
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff813260c0-ffffffff81326117: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135ff5e)
Location: fs/block_dev.c:2210
Inline: True
Inline callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
Direct callers:
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff8135f460-ffffffff8135f4b7: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136cbc0)
Location: fs/block_dev.c:1885
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8136cbc0-ffffffff8136cc17: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81373460)
Location: fs/block_dev.c:1894
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:delete_partition
```
**Symbols:**

```
ffffffff81373460-ffffffff813734b7: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c3d30)
Location: block/bdev.c:998
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:delete_partition
```
**Symbols:**

```
ffffffff815c3d30-ffffffff815c3d87: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166ea20)
Location: block/bdev.c:1002
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:delete_partition
```
**Symbols:**

```
ffffffff8166ea20-ffffffff8166eabf: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81729cf0)
Location: block/bdev.c:1001
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:delete_partition
```
**Symbols:**

```
ffffffff81729cf0-ffffffff81729d8f: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81766060)
Location: block/bdev.c:963
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:bdev_del_partition
```
**Symbols:**

```
ffffffff81766060-ffffffff817660fc: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e02f0)
Location: fs/block_dev.c:2191
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffff8000103e02f0-ffff8000103e037c: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b9190)
Location: fs/block_dev.c:2191
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
c05b9190-c05b91e8: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e5fd0)
Location: fs/block_dev.c:2191
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
c0000000004e5fd0-c0000000004e609c: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000297090)
Location: fs/block_dev.c:2191
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffe000297090-ffffffe0002970fa: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131e6a0)
Location: fs/block_dev.c:2191
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff8131e6a0-ffffffff8131e6f7: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130f240)
Location: fs/block_dev.c:2191
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff8130f240-ffffffff8130f297: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131c170)
Location: fs/block_dev.c:2191
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff8131c170-ffffffff8131c1c7: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __invalidate_device(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132e280)
Location: fs/block_dev.c:2191
Inline: False
Direct callers:
  - fs/block_dev.c:flush_disk
  - block/genhd.c:invalidate_partition
```
**Symbols:**

```
ffffffff8132e280-ffffffff8132e2d7: __invalidate_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
