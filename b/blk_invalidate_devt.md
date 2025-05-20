# Function: <code>blk_invalidate_devt</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814e10e3)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff814dfb80-ffffffff814dfbbd: blk_invalidate_devt.part.0 (STB_LOCAL)
ffffffff814e0bc0-ffffffff814e0bdd: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814fa51d)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff814f8fb0-ffffffff814f8fed: blk_invalidate_devt.part.0 (STB_LOCAL)
ffffffff814f9ff0-ffffffff814fa00d: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155b4b4)
Location: block/genhd.c:624
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
Direct callers:
  - block/partitions/core.c:delete_partition
```
**Symbols:**

```
ffffffff8155ad40-ffffffff8155ad8d: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffff8000105fc0d4)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffff8000105fa7b8-ffff8000105fa880: blk_invalidate_devt.part.0 (STB_LOCAL)
ffff8000105fbb20-ffff8000105fbb64: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (c07a713c)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
c07a5500-c07a5548: blk_invalidate_devt.part.0 (STB_LOCAL)
c07a6bf4-c07a6c1c: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (c000000000795578)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
c0000000007935c0-c000000000793638: blk_invalidate_devt.part.0 (STB_LOCAL)
c000000000794e30-c000000000794e50: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffe0004380ba)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffe000436b26-ffffffe000436b7e: blk_invalidate_devt.part.0 (STB_LOCAL)
ffffffe000437bd0-ffffffe000437c10: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814f2afd)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff814f1590-ffffffff814f15cd: blk_invalidate_devt.part.0 (STB_LOCAL)
ffffffff814f25d0-ffffffff814f25ed: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814e302d)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff814e1ad0-ffffffff814e1b0d: blk_invalidate_devt.part.0 (STB_LOCAL)
ffffffff814e2b00-ffffffff814e2b1d: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814eeb8d)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff814ed620-ffffffff814ed65d: blk_invalidate_devt.part.0 (STB_LOCAL)
ffffffff814ee660-ffffffff814ee67d: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_invalidate_devt(dev_t devt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff81507c37)
Location: block/genhd.c:538
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
Direct callers:
  - block/genhd.c:del_gendisk
  - block/partition-generic.c:delete_partition
```
**Symbols:**

```
ffffffff81506830-ffffffff8150686d: blk_invalidate_devt.part.0 (STB_LOCAL)
ffffffff81507700-ffffffff8150771d: blk_invalidate_devt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
