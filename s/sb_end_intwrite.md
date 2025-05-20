# Function: <code>sb_end_intwrite</code>

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
In fs/ext4/inode.c (ffffffff8129d9cf)
Location: include/linux/fs.h:1431
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/inode.c (ffffffff812cb6a6)
Location: include/linux/fs.h:1508
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/inode.c (ffffffff812e1386)
Location: include/linux/fs.h:1474
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/inode.c (ffffffff813056a5)
Location: include/linux/fs.h:1490
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/inode.c (ffffffff8132a20a)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff81343d95)
Location: include/linux/fs.h:1530
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81358647)
Location: include/linux/fs.h:1530
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff8135bed5)
Location: include/linux/fs.h:1585
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81370977)
Location: include/linux/fs.h:1585
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff81385072)
Location: include/linux/fs.h:1601
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81399ed0)
Location: include/linux/fs.h:1601
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff8139db12)
Location: include/linux/fs.h:1627
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813b2982)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff813e8b62)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/inode.c (ffffffff813fe65e)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff813fb14d)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/inode.c (ffffffff81410f2a)
Location: include/linux/fs.h:1638
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff8140161d)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/inode.c (ffffffff814172e6)
Location: include/linux/fs.h:1807
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81453ba6)
Location: include/linux/fs.h:1857
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/inode.c (ffffffff8146a6b0)
Location: include/linux/fs.h:1857
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff814d1089)
Location: include/linux/fs.h:1748
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/inode.c (ffffffff814ea64e)
Location: include/linux/fs.h:1748
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81569acd)
Location: include/linux/fs.h:1863
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/inode.c (ffffffff81584190)
Location: include/linux/fs.h:1863
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815a18bd)
Location: include/linux/fs.h:1543
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/inode.c (ffffffff815baada)
Location: include/linux/fs.h:1543
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815da66d)
Location: include/linux/fs.h:1751
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_sample_last_mounted
```
```
In fs/ext4/inode.c (ffffffff815f384a)
Location: include/linux/fs.h:1751
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffff800010471038)
Location: include/linux/fs.h:1627
Inline: True
```
```
In fs/ext4/inode.c (ffff800010487208)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (c0631da8)
Location: include/linux/fs.h:1627
Inline: True
```
```
In fs/ext4/inode.c (c06491ac)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (c000000000591874)
Location: include/linux/fs.h:1627
Inline: True
```
```
In fs/ext4/inode.c (c0000000005ad550)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffe0002fd3d4)
Location: include/linux/fs.h:1627
Inline: True
```
```
In fs/ext4/inode.c (ffffffe00030efcc)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff813960f2)
Location: include/linux/fs.h:1627
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813aaf62)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff81386b82)
Location: include/linux/fs.h:1627
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8139b9f2)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff81393a52)
Location: include/linux/fs.h:1627
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813a87c2)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
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
In fs/ext4/file.c (ffffffff813a7ae2)
Location: include/linux/fs.h:1627
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813bd063)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
</details>
</li>
</ul>

## Differences
