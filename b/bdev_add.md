# Function: <code>bdev_add</code>

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
void bdev_add(struct block_device *bdev, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e7e0)
Location: fs/block_dev.c:911
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff8136e7e0-ffffffff8136e80c: bdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bdev_add(struct block_device *bdev, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813750f0)
Location: fs/block_dev.c:917
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff813750f0-ffffffff8137511c: bdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bdev_add(struct block_device *bdev, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4aa0)
Location: block/bdev.c:504
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff815c4aa0-ffffffff815c4acc: bdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bdev_add(struct block_device *bdev, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166f4e0)
Location: block/bdev.c:509
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff8166f4e0-ffffffff8166f518: bdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bdev_add(struct block_device *bdev, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a880)
Location: block/bdev.c:508
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff8172a880-ffffffff8172a8b8: bdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bdev_add(struct block_device *bdev, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81766ad0)
Location: block/bdev.c:443
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff81766ad0-ffffffff81766b08: bdev_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bdev_add(struct block_device *bdev, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff817a86f0)
Location: block/bdev.c:432
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff817a86f0-ffffffff817a8742: bdev_add (STB_GLOBAL)
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
