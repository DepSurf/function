# Function: <code>bdev_unhash_inode</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81292de0)
Location: fs/block_dev.c:862
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81292de0-ffffffff81292e4b: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b5bd0)
Location: fs/block_dev.c:852
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff812b5bd0-ffffffff812b5c3b: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd830)
Location: fs/block_dev.c:853
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff812dd830-ffffffff812dd89c: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2e10)
Location: fs/block_dev.c:892
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff812f2e10-ffffffff812f2e7c: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314870)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81314870-ffffffff813148e1: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81327050)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff81327050-ffffffff813270c1: bdev_unhash_inode (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1de0)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffff8000103e1de0-ffff8000103e1e54: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05ba0c8)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
c05ba0c8-c05ba13c: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e78e0)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
c0000000004e78e0-c0000000004e797c: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002984b2)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffe0002984b2-ffffffe000298524: bdev_unhash_inode (STB_GLOBAL)
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
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f630)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8131f630-ffffffff8131f6a1: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813101d0)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff813101d0-ffffffff81310241: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d100)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8131d100-ffffffff8131d171: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bdev_unhash_inode(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ede0)
Location: fs/block_dev.c:889
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
```
**Symbols:**

```
ffffffff8132ede0-ffffffff8132ee51: bdev_unhash_inode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
