# Function: <code>blockdev_direct_IO</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812d9bdd)
Location: include/linux/fs.h:2715
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_direct_IO
```
```
In fs/fat/inode.c (ffffffff812fc9ca)
Location: include/linux/fs.h:2715
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff8133067f)
Location: include/linux/fs.h:2862
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff813463df)
Location: include/linux/fs.h:2828
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff8135ae0f)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff8137fb0f)
Location: include/linux/fs.h:3018
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff813adfdf)
Location: include/linux/fs.h:3039
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff813c750f)
Location: include/linux/fs.h:3114
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff813f1fff)
Location: include/linux/fs.h:3125
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff8140beff)
Location: include/linux/fs.h:3187
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81459dff)
Location: include/linux/fs.h:3243
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8147614f)
Location: include/linux/fs.h:3043
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff8147bbbf)
Location: include/linux/fs.h:3296
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff814d330b)
Location: include/linux/fs.h:3277
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff815606db)
Location: include/linux/fs.h:3057
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff81602c0b)
Location: include/linux/fs.h:3211
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff8163ab2b)
Location: include/linux/fs.h:2831
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff8167405b)
Location: include/linux/fs.h:3112
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffff8000104ec818)
Location: include/linux/fs.h:3187
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (c06a9650)
Location: include/linux/fs.h:3187
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (c000000000629ac0)
Location: include/linux/fs.h:3187
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffe00035bf30)
Location: include/linux/fs.h:3187
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff814044df)
Location: include/linux/fs.h:3187
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff813f4f5f)
Location: include/linux/fs.h:3187
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff8140185f)
Location: include/linux/fs.h:3187
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
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
In fs/fat/inode.c (ffffffff8141798f)
Location: include/linux/fs.h:3187
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_direct_IO
```
</details>
</li>
</ul>

## Differences
