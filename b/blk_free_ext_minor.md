# Function: <code>blk_free_ext_minor</code>

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
void blk_free_ext_minor(unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e3b69)
Location: block/genhd.c:333
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/bdev.c:bdev_free_inode
```
**Symbols:**

```
ffffffff815e47a0-ffffffff815e47b9: blk_free_ext_minor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_free_ext_minor(unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8169363d)
Location: block/genhd.c:344
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/bdev.c:bdev_free_inode
```
**Symbols:**

```
ffffffff816933c0-ffffffff816933e1: blk_free_ext_minor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_free_ext_minor(unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81752312)
Location: block/genhd.c:321
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/bdev.c:bdev_free_inode
```
**Symbols:**

```
ffffffff81752040-ffffffff81752061: blk_free_ext_minor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_free_ext_minor(unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178e514)
Location: block/genhd.c:317
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/bdev.c:bdev_free_inode
```
**Symbols:**

```
ffffffff8178e7e0-ffffffff8178e801: blk_free_ext_minor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_free_ext_minor(unsigned int minor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817d0dba)
Location: block/genhd.c:317
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/bdev.c:bdev_free_inode
```
**Symbols:**

```
ffffffff817d10a0-ffffffff817d10c1: blk_free_ext_minor (STB_GLOBAL)
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
