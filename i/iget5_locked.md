# Function: <code>iget5_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812286c0)
Location: fs/inode.c:1009
Inline: False
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff812286c0-ffffffff812288c7: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81250df0)
Location: fs/inode.c:1018
Inline: False
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81250df0-ffffffff81250fd4: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81263ef0)
Location: fs/inode.c:1020
Inline: False
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
```
**Symbols:**

```
ffffffff81263ef0-ffffffff812640d0: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812718b0)
Location: fs/inode.c:1021
Inline: False
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812718b0-ffffffff81271a90: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812941d0)
Location: fs/inode.c:1021
Inline: False
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812941d0-ffffffff812943b3: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812baab0)
Location: fs/inode.c:1090
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812baab0-ffffffff812bab2f: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cf3c0)
Location: fs/inode.c:1116
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812cf3c0-ffffffff812cf44a: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ec2f0)
Location: fs/inode.c:1129
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812ec2f0-ffffffff812ec37a: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fde40)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812fde40-ffffffff812fdeca: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81337320)
Location: fs/inode.c:1141
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81337320-ffffffff813373aa: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81342c60)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81342c60-ffffffff81342cea: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348e70)
Location: fs/inode.c:1147
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81348e70-ffffffff81348efa: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81396bb0)
Location: fs/inode.c:1151
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81396bb0-ffffffff81396c3a: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81418910)
Location: fs/inode.c:1232
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81418910-ffffffff814189b3: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a4220)
Location: fs/inode.c:1234
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff814a4220-ffffffff814a42c3: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d93a0)
Location: fs/inode.c:1278
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff814d93a0-ffffffff814d9443: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff8150bb9e)
Location: fs/inode.c:1226
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff821c5181-ffffffff821c519e: iget5_locked.cold (STB_LOCAL)
ffffffff8150ba90-ffffffff8150bbf8: iget5_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ae6d8)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffff8000103ae6d8-ffff8000103ae77c: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058ef40)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
c058ef40-c058efc8: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004aaa90)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
c0000000004aaa90-c0000000004aab60: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000273458)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffe000273458-ffffffe0002734de: iget5_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f6420)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812f6420-ffffffff812f64aa: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e7040)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812e7040-ffffffff812e70ca: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4230)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff812f4230-ffffffff812f42ba: iget5_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct inode *iget5_locked(struct super_block *sb, long unsigned int hashval, int (*test)(struct inode *, void *), int (*set)(struct inode *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81305930)
Location: fs/inode.c:1140
Inline: True
Direct callers:
  - fs/block_dev.c:bdget
  - fs/fuse/inode.c:fuse_iget
  - drivers/dax/super.c:alloc_dax
```
**Symbols:**

```
ffffffff81305930-ffffffff813059ba: iget5_locked (STB_GLOBAL)
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
