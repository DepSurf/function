# Function: <code>ext4_xattr_block_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812dcd70)
Location: fs/ext4/xattr.c:120
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff812dcd70-ffffffff812dce50: ext4_xattr_block_csum.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130c7d0)
Location: fs/ext4/xattr.c:118
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff8130c7d0-ffffffff8130c91c: ext4_xattr_block_csum.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813226f0)
Location: fs/ext4/xattr.c:112
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff813226f0-ffffffff8132283c: ext4_xattr_block_csum.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133a350)
Location: fs/ext4/xattr.c:126
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff8133a350-ffffffff8133a496: ext4_xattr_block_csum.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8135e720)
Location: fs/ext4/xattr.c:127
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff8135e720-ffffffff8135e866: ext4_xattr_block_csum.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138d070)
Location: fs/ext4/xattr.c:128
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff8138d070-ffffffff8138d1b6: ext4_xattr_block_csum.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a5c80)
Location: fs/ext4/xattr.c:128
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff813a5c80-ffffffff813a5dc6: ext4_xattr_block_csum.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813cfce0)
Location: fs/ext4/xattr.c:128
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff813cfce0-ffffffff813cfe06: ext4_xattr_block_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e93b0)
Location: fs/ext4/xattr.c:128
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff813e93b0-ffffffff813e94d6: ext4_xattr_block_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81436da0)
Location: fs/ext4/xattr.c:130
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff81436da0-ffffffff81436ec5: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144f8a0)
Location: fs/ext4/xattr.c:130
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff8144f8a0-ffffffff8144f9c5: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81455090)
Location: fs/ext4/xattr.c:130
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff81455090-ffffffff814551b5: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a91b0)
Location: fs/ext4/xattr.c:130
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff814a91b0-ffffffff814a92d5: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81530bc0)
Location: fs/ext4/xattr.c:130
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff81530bc0-ffffffff81530d4b: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815cf200)
Location: fs/ext4/xattr.c:132
Inline: False
Direct callers:
  - fs/ext4/xattr.c:__ext4_xattr_check_block
```
**Symbols:**

```
ffffffff815cf200-ffffffff815cf38b: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81606ae0)
Location: fs/ext4/xattr.c:132
Inline: False
Direct callers:
  - fs/ext4/xattr.c:check_xattrs
```
**Symbols:**

```
ffffffff81606ae0-ffffffff81606c6b: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8163f820)
Location: fs/ext4/xattr.c:132
Inline: False
Direct callers:
  - fs/ext4/xattr.c:check_xattrs
```
**Symbols:**

```
ffffffff8163f820-ffffffff8163f9ab: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c2170)
Location: fs/ext4/xattr.c:128
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffff8000104c2170-ffff8000104c2238: ext4_xattr_block_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0686264)
Location: fs/ext4/xattr.c:128
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
c0686264-c0686330: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005f91a0)
Location: fs/ext4/xattr.c:128
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
c0000000005f91a0-c0000000005f9338: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__le32 ext4_xattr_block_csum(struct inode *inode, sector_t block_nr, struct ext4_xattr_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033d7ec)
Location: fs/ext4/xattr.c:128
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffe00033d7ec-ffffffe00033d8ec: ext4_xattr_block_csum (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e1990)
Location: fs/ext4/xattr.c:128
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff813e1990-ffffffff813e1ab6: ext4_xattr_block_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d2410)
Location: fs/ext4/xattr.c:128
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff813d2410-ffffffff813d2536: ext4_xattr_block_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ded10)
Location: fs/ext4/xattr.c:128
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff813ded10-ffffffff813dee36: ext4_xattr_block_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f4130)
Location: fs/ext4/xattr.c:128
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_csum_verify
```
**Symbols:**

```
ffffffff813f4130-ffffffff813f4256: ext4_xattr_block_csum.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
