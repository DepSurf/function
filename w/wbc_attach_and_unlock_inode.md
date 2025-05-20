# Function: <code>wbc_attach_and_unlock_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8123b340)
Location: fs/fs-writeback.c:516
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8123b340-ffffffff8123b46a: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812631f0)
Location: fs/fs-writeback.c:518
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812631f0-ffffffff8126331a: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81276640)
Location: fs/fs-writeback.c:518
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81276640-ffffffff8127676a: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81283ac0)
Location: fs/fs-writeback.c:532
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81283ac0-ffffffff81283be4: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a6670)
Location: fs/fs-writeback.c:532
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812a6670-ffffffff812a6794: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812cd240)
Location: fs/fs-writeback.c:532
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812cd240-ffffffff812cd361: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e2560)
Location: fs/fs-writeback.c:555
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812e2560-ffffffff812e2681: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813005b0)
Location: fs/fs-writeback.c:558
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff813005b0-ffffffff813006da: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81312bf0)
Location: fs/fs-writeback.c:557
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81312bf0-ffffffff81312d2d: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134c540)
Location: fs/fs-writeback.c:558
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8134c540-ffffffff8134c5f9: wbc_attach_and_unlock_inode.part.0 (STB_LOCAL)
ffffffff8134c600-ffffffff8134c68e: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fs-writeback.c (ffffffff81359540)
Location: fs/fs-writeback.c:558
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81359540-ffffffff81359608: wbc_attach_and_unlock_inode.part.0 (STB_LOCAL)
ffffffff81359610-ffffffff81359699: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81360170)
Location: fs/fs-writeback.c:564
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81360170-ffffffff813602af: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813ae7f0)
Location: fs/fs-writeback.c:688
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff813ae7f0-ffffffff813ae93a: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81433010)
Location: fs/fs-writeback.c:691
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81433010-ffffffff81433122: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c1000)
Location: fs/fs-writeback.c:693
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff814c1000-ffffffff814c1112: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f62b0)
Location: fs/fs-writeback.c:693
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff814f62b0-ffffffff814f63c2: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152a9f0)
Location: fs/fs-writeback.c:710
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8152a9f0-ffffffff8152ab02: wbc_attach_and_unlock_inode (STB_GLOBAL)
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
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c8120)
Location: fs/fs-writeback.c:557
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffff8000103c8120-ffff8000103c826c: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a2808)
Location: fs/fs-writeback.c:557
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
c05a2808-c05a29ac: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c66b0)
Location: fs/fs-writeback.c:557
Inline: True
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
c0000000004c66b0-c0000000004c68e0: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000286b10)
Location: fs/fs-writeback.c:557
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffe000286b10-ffffffe000286ca6: wbc_attach_and_unlock_inode (STB_GLOBAL)
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
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130b1d0)
Location: fs/fs-writeback.c:557
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8130b1d0-ffffffff8130b30d: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fbdf0)
Location: fs/fs-writeback.c:557
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812fbdf0-ffffffff812fbf2d: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81308fc0)
Location: fs/fs-writeback.c:557
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81308fc0-ffffffff813090fd: wbc_attach_and_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wbc_attach_and_unlock_inode(struct writeback_control *wbc, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131acc0)
Location: fs/fs-writeback.c:557
Inline: False
Direct callers:
  - mm/filemap.c:__filemap_fdatawrite_range
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8131acc0-ffffffff8131ae10: wbc_attach_and_unlock_inode (STB_GLOBAL)
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
