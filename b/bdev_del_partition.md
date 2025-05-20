# Function: <code>bdev_del_partition</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bdev_del_partition(struct block_device *bdev, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff8155d950)
Location: block/partitions/core.c:524
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff8155d950-ffffffff8155da43: bdev_del_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bdev_del_partition(struct block_device *bdev, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81579820)
Location: block/partitions/core.c:468
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81579820-ffffffff815798b7: bdev_del_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bdev_del_partition(struct block_device *bdev, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815814f0)
Location: block/partitions/core.c:465
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff815814f0-ffffffff81581577: bdev_del_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bdev_del_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff815e6890)
Location: block/partitions/core.c:479
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff815e6890-ffffffff815e68f4: bdev_del_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bdev_del_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81695a00)
Location: block/partitions/core.c:470
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81695a00-ffffffff81695a67: bdev_del_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bdev_del_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81754c20)
Location: block/partitions/core.c:469
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81754c20-ffffffff81754c8a: bdev_del_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bdev_del_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff81791300)
Location: block/partitions/core.c:477
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff81791300-ffffffff817913e1: bdev_del_partition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bdev_del_partition(struct gendisk *disk, int partno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/core.c (ffffffff817d4c20)
Location: block/partitions/core.c:460
Inline: False
Direct callers:
  - block/ioctl.c:blkpg_do_ioctl
```
**Symbols:**

```
ffffffff817d4c20-ffffffff817d4cf0: bdev_del_partition (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
</ul>
</details>
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
