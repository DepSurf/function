# Function: <code>ilookup5</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81228400)
Location: fs/inode.c:1257
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81228400-ffffffff81228455: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81250b30)
Location: fs/inode.c:1266
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81250b30-ffffffff81250b85: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263bd0)
Location: fs/inode.c:1284
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81263bd0-ffffffff81263c5b: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81271590)
Location: fs/inode.c:1285
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81271590-ffffffff8127161b: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293eb0)
Location: fs/inode.c:1285
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81293eb0-ffffffff81293f3b: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812ba170)
Location: fs/inode.c:1306
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff812ba170-ffffffff812ba1fb: ilookup5.part.28 (STB_LOCAL)
ffffffff812ba200-ffffffff812ba210: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812cf170)
Location: fs/inode.c:1337
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff812cf170-ffffffff812cf1fb: ilookup5.part.29 (STB_LOCAL)
ffffffff812cf200-ffffffff812cf210: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ec0b0)
Location: fs/inode.c:1350
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff812ec0b0-ffffffff812ec13e: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fdc00)
Location: fs/inode.c:1361
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff812fdc00-ffffffff812fdc8e: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81336b70)
Location: fs/inode.c:1359
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81336b70-ffffffff81336c0b: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813424b0)
Location: fs/inode.c:1358
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_ilookup
```
**Symbols:**

```
ffffffff813424b0-ffffffff8134254b: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348de0)
Location: fs/inode.c:1365
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_ilookup
```
**Symbols:**

```
ffffffff81348de0-ffffffff81348e6e: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1369
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_ilookup
```
**Symbols:**

```
ffffffff81cc3d48-ffffffff81cc3d65: ilookup5.cold (STB_LOCAL)
ffffffff81396aa0-ffffffff81396ba8: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1450
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_ilookup
```
**Symbols:**

```
ffffffff81e76507-ffffffff81e76523: ilookup5.cold (STB_LOCAL)
ffffffff814183b0-ffffffff814184bc: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1452
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_ilookup
```
**Symbols:**

```
ffffffff82068aa2-ffffffff82068abe: ilookup5.cold (STB_LOCAL)
ffffffff814a3d70-ffffffff814a3e81: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1496
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_ilookup
```
**Symbols:**

```
ffffffff820e83e0-ffffffff820e83fc: ilookup5.cold (STB_LOCAL)
ffffffff814d8ef0-ffffffff814d9001: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff8150baa8)
Location: fs/inode.c:1444
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_ilookup
```
**Symbols:**

```
ffffffff821c511d-ffffffff821c5139: ilookup5.cold (STB_LOCAL)
ffffffff8150b5f0-ffffffff8150b6fe: ilookup5 (STB_GLOBAL)
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
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ae638)
Location: fs/inode.c:1361
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffff8000103ae638-ffff8000103ae6d8: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058e9e8)
Location: fs/inode.c:1361
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
c058e9e8-c058ea78: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a9a20)
Location: fs/inode.c:1361
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
c0000000004a9a20-c0000000004a9afc: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe0002731c2)
Location: fs/inode.c:1361
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffe0002731c2-ffffffe000273252: ilookup5 (STB_GLOBAL)
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
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f61e0)
Location: fs/inode.c:1361
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff812f61e0-ffffffff812f626e: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e6e00)
Location: fs/inode.c:1361
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff812e6e00-ffffffff812e6e8e: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f3ff0)
Location: fs/inode.c:1361
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff812f3ff0-ffffffff812f407e: ilookup5 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *ilookup5(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81305290)
Location: fs/inode.c:1361
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/block_dev.c:bdev_unhash_inode
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/inode.c:fuse_get_dentry
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81305290-ffffffff81305313: ilookup5 (STB_GLOBAL)
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
