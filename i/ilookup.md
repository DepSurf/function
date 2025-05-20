# Function: <code>ilookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81228460)
Location: fs/inode.c:1276
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81228460-ffffffff81228526: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81250b90)
Location: fs/inode.c:1285
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81250b90-ffffffff81250c59: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263c60)
Location: fs/inode.c:1309
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81263c60-ffffffff81263d3b: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81271620)
Location: fs/inode.c:1310
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81271620-ffffffff812716fb: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293f40)
Location: fs/inode.c:1310
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81293f40-ffffffff8129401b: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ba210)
Location: fs/inode.c:1331
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812ba210-ffffffff812ba2eb: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cf540)
Location: fs/inode.c:1362
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812cf540-ffffffff812cf62c: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ec480)
Location: fs/inode.c:1375
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812ec480-ffffffff812ec57a: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fdfd0)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812fdfd0-ffffffff812fe0ca: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81336c10)
Location: fs/inode.c:1384
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81336c10-ffffffff81336d16: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81342550)
Location: fs/inode.c:1383
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get_no_open
  - fs/block_dev.c:blkdev_get_no_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81342550-ffffffff81342656: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348f00)
Location: fs/inode.c:1390
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_get_no_open
  - fs/block_dev.c:blkdev_get_no_open
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
```
**Symbols:**

```
ffffffff81348f00-ffffffff81348ffa: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1394
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_get_no_open
```
**Symbols:**

```
ffffffff81cc3d65-ffffffff81cc3d89: ilookup.cold (STB_LOCAL)
ffffffff81396c40-ffffffff81396d3f: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1475
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_get_no_open
```
**Symbols:**

```
ffffffff81e7654f-ffffffff81e76573: ilookup.cold (STB_LOCAL)
ffffffff814185a0-ffffffff814186bc: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1477
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_get_no_open
```
**Symbols:**

```
ffffffff82068abe-ffffffff82068ae2: ilookup.cold (STB_LOCAL)
ffffffff814a3ea0-ffffffff814a3fa8: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1521
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_get_no_open
```
**Symbols:**

```
ffffffff820e83fc-ffffffff820e8420: ilookup.cold (STB_LOCAL)
ffffffff814d9020-ffffffff814d9128: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1469
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - block/bdev.c:blkdev_get_no_open
  - block/bdev.c:blkdev_get_no_open
```
**Symbols:**

```
ffffffff821c5139-ffffffff821c515d: ilookup.cold (STB_LOCAL)
ffffffff8150b710-ffffffff8150b813: ilookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ae780)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffff8000103ae780-ffff8000103ae8ec: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058ea78)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
c058ea78-c058eb7c: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a9b00)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
c0000000004a9b00-c0000000004a9cec: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000273654)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffe000273654-ffffffe000273784: ilookup (STB_GLOBAL)
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
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f65b0)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812f65b0-ffffffff812f66aa: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e71d0)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812e71d0-ffffffff812e72ca: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f43c0)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812f43c0-ffffffff812f44ba: ilookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *ilookup(struct super_block *sb, long unsigned int ino);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81305320)
Location: fs/inode.c:1386
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81305320-ffffffff81305405: ilookup (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
