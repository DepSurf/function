# Function: <code>ext4_issue_zeroout</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c5bf0)
Location: fs/ext4/inode.c:389
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_zeroout
```
**Symbols:**

```
ffffffff812c5bf0-ffffffff812c5c4c: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812db420)
Location: fs/ext4/inode.c:396
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_zeroout
```
**Symbols:**

```
ffffffff812db420-ffffffff812db47c: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812ffcd0)
Location: fs/ext4/inode.c:402
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff812ffcd0-ffffffff812ffd29: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813244f0)
Location: fs/ext4/inode.c:412
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813244f0-ffffffff81324549: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81352720)
Location: fs/ext4/inode.c:413
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81352720-ffffffff81352779: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136a840)
Location: fs/ext4/inode.c:413
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8136a840-ffffffff8136a899: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81393d50)
Location: fs/ext4/inode.c:417
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81393d50-ffffffff81393da8: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ac6e0)
Location: fs/ext4/inode.c:426
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813ac6e0-ffffffff813ac738: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f89b0)
Location: fs/ext4/inode.c:407
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813f89b0-ffffffff813f8a1a: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140b080)
Location: fs/ext4/inode.c:418
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8140b080-ffffffff8140b0ea: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81411240)
Location: fs/ext4/inode.c:419
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81411240-ffffffff814112a0: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:418
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81ccab2b-ffffffff81ccab67: ext4_issue_zeroout.cold (STB_LOCAL)
ffffffff81464070-ffffffff814640ec: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:417
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81e7d92c-ffffffff81e7d96a: ext4_issue_zeroout.cold (STB_LOCAL)
ffffffff814e35b0-ffffffff814e363e: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:423
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8206de96-ffffffff8206ded4: ext4_issue_zeroout.cold (STB_LOCAL)
ffffffff8157caa0-ffffffff8157cb2e: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:395
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff820edb85-ffffffff820edbc3: ext4_issue_zeroout.cold (STB_LOCAL)
ffffffff815b3ea0-ffffffff815b3f2e: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:395
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff821cacb4-ffffffff821cacf2: ext4_issue_zeroout.cold (STB_LOCAL)
ffffffff815ecca0-ffffffff815ecd2e: ext4_issue_zeroout (STB_GLOBAL)
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
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010480e78)
Location: fs/ext4/inode.c:426
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffff800010480e78-ffff800010480f08: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0641f5c)
Location: fs/ext4/inode.c:426
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c0641f5c-c0641ff0: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a52b0)
Location: fs/ext4/inode.c:426
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c0000000005a52b0-c0000000005a5348: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000309bc8)
Location: fs/ext4/inode.c:426
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffe000309bc8-ffffffe000309c5e: ext4_issue_zeroout (STB_GLOBAL)
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
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4cc0)
Location: fs/ext4/inode.c:426
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813a4cc0-ffffffff813a4d18: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395750)
Location: fs/ext4/inode.c:426
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81395750-ffffffff813957a8: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a2520)
Location: fs/ext4/inode.c:426
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813a2520-ffffffff813a2578: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_issue_zeroout(struct inode *inode, ext4_lblk_t lblk, ext4_fsblk_t pblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b6c00)
Location: fs/ext4/inode.c:426
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_zeroout
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813b6c00-ffffffff813b6c58: ext4_issue_zeroout (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
