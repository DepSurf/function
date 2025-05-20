# Function: <code>fat_iget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fdb10)
Location: fs/fat/inode.c:405
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff812fdb10-ffffffff812fdbb4: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81331aa0)
Location: fs/fat/inode.c:436
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81331aa0-ffffffff81331b44: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81347840)
Location: fs/fat/inode.c:436
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81347840-ffffffff813478e4: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8135c270)
Location: fs/fat/inode.c:436
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8135c270-ffffffff8135c31b: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81380f70)
Location: fs/fat/inode.c:436
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81380f70-ffffffff8138101b: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813af710)
Location: fs/fat/inode.c:443
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813af710-ffffffff813af7bb: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813c8bc0)
Location: fs/fat/inode.c:443
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813c8bc0-ffffffff813c8c6b: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813f3740)
Location: fs/fat/inode.c:444
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813f3740-ffffffff813f37dd: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8140d620)
Location: fs/fat/inode.c:449
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8140d620-ffffffff8140d6bd: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8145b390)
Location: fs/fat/inode.c:449
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8145b390-ffffffff8145b42d: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff814776e0)
Location: fs/fat/inode.c:449
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff814776e0-ffffffff8147777d: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8147d160)
Location: fs/fat/inode.c:449
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
```
**Symbols:**

```
ffffffff8147d160-ffffffff8147d1fd: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff814d48e0)
Location: fs/fat/inode.c:450
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
```
**Symbols:**

```
ffffffff814d48e0-ffffffff814d497d: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81561870)
Location: fs/fat/inode.c:451
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
```
**Symbols:**

```
ffffffff81561870-ffffffff8156191c: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81603f90)
Location: fs/fat/inode.c:446
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
```
**Symbols:**

```
ffffffff81603f90-ffffffff8160403c: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8163beb0)
Location: fs/fat/inode.c:446
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
```
**Symbols:**

```
ffffffff8163beb0-ffffffff8163bf5c: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81675410)
Location: fs/fat/inode.c:446
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
```
**Symbols:**

```
ffffffff81675410-ffffffff816754bc: fat_iget (STB_GLOBAL)
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
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104ee3a8)
Location: fs/fat/inode.c:449
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffff8000104ee3a8-ffff8000104ee4a0: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06abfc0)
Location: fs/fat/inode.c:449
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
c06abfc0-c06ac080: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c00000000062d320)
Location: fs/fat/inode.c:449
Inline: False
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
c00000000062d320-c00000000062d448: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035e73e)
Location: fs/fat/inode.c:449
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffe00035e73e-ffffffe00035e806: fat_iget (STB_GLOBAL)
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
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81405c00)
Location: fs/fat/inode.c:449
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81405c00-ffffffff81405c9d: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813f6680)
Location: fs/fat/inode.c:449
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813f6680-ffffffff813f671d: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81402f80)
Location: fs/fat/inode.c:449
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81402f80-ffffffff8140301d: fat_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct inode *fat_iget(struct super_block *sb, loff_t i_pos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81418be0)
Location: fs/fat/inode.c:449
Inline: True
Direct callers:
  - fs/fat/dir.c:__fat_readdir
  - fs/fat/inode.c:fat_build_inode
  - fs/fat/nfs.c:__fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81418be0-ffffffff81418c84: fat_iget (STB_GLOBAL)
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
