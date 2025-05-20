# Function: <code>dget_dlock</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff812de2b5)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/configfs/inode.c (ffffffff81302bf5)
Location: include/linux/dcache.h:315
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/configfs/inode.c (ffffffff81330b34)
Location: include/linux/dcache.h:316
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/configfs/inode.c (ffffffff81347f24)
Location: include/linux/dcache.h:313
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/configfs/inode.c (ffffffff813703a7)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff8130cad7)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81388897)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff81345ed6)
Location: include/linux/dcache.h:313
Inline: True
Inline callers:
  - fs/libfs.c:find_next_child
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff813d35d7)
Location: include/linux/dcache.h:313
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff81352396)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/libfs.c:find_next_child
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff813e5317)
Location: include/linux/dcache.h:314
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff81358dd2)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff813ebf27)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff813a7632)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff8143dcc7)
Location: include/linux/dcache.h:317
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff8142c18a)
Location: include/linux/dcache.h:307
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff814b95b4)
Location: include/linux/dcache.h:307
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff814b989a)
Location: include/linux/dcache.h:310
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81550d34)
Location: include/linux/dcache.h:310
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff814ee89a)
Location: include/linux/dcache.h:310
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81588a14)
Location: include/linux/dcache.h:310
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/dcache.c (ffffffff81505ac7)
Location: include/linux/dcache.h:300
Inline: True
Inline callers:
  - fs/dcache.c:d_exact_alias
  - fs/dcache.c:d_alloc
  - fs/dcache.c:find_submount
  - fs/dcache.c:d_find_alias
```
```
In fs/libfs.c (ffffffff81522876)
Location: include/linux/dcache.h:300
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
  - fs/libfs.c:offset_iterate_dir
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff815c15e4)
Location: include/linux/dcache.h:300
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffff8000103c150c)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffff800010458b74)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (c059cbd4)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (c061a8f8)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (c0000000004be818)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (c000000000573628)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffe000281828)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffe0002e9b3e)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff813050b7)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81380e77)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff812f5cd7)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81371907)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff81302ea7)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff8137e947)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
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
In fs/libfs.c (ffffffff81313f35)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/libfs.c:scan_positives
```
```
In fs/configfs/inode.c (ffffffff81392457)
Location: include/linux/dcache.h:311
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_drop_dentry
```
</details>
</li>
</ul>

## Differences
