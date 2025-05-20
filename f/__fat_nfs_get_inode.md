# Function: <code>__fat_nfs_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff812fe970)
Location: fs/fat/nfs.c:65
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_nfs_get_inode
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
```
**Symbols:**

```
ffffffff812fe970-ffffffff812feab8: __fat_nfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81332970)
Location: fs/fat/nfs.c:65
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81332970-ffffffff81332ab8: __fat_nfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81348710)
Location: fs/fat/nfs.c:65
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81348710-ffffffff81348858: __fat_nfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff8135d270)
Location: fs/fat/nfs.c:65
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8135d270-ffffffff8135d3ba: __fat_nfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffff81381f70)
Location: fs/fat/nfs.c:65
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81381f70-ffffffff813820ba: __fat_nfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:65
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813b08d0-ffffffff813b09f6: __fat_nfs_get_inode (STB_LOCAL)
ffffffff813b0de4-ffffffff813b0e04: __fat_nfs_get_inode.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:65
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813c9f30-ffffffff813ca056: __fat_nfs_get_inode (STB_LOCAL)
ffffffff813ca444-ffffffff813ca464: __fat_nfs_get_inode.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813f4ab0-ffffffff813f4bd7: __fat_nfs_get_inode (STB_LOCAL)
ffffffff813f4fd4-ffffffff813f4ff4: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8140e980-ffffffff8140eaa7: __fat_nfs_get_inode (STB_LOCAL)
ffffffff8140eea4-ffffffff8140eec4: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8145ca30-ffffffff8145cb51: __fat_nfs_get_inode (STB_LOCAL)
ffffffff8145ccf2-ffffffff8145cd12: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81478760-ffffffff81478881: __fat_nfs_get_inode (STB_LOCAL)
ffffffff81bedf1d-ffffffff81bedf3d: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (ffffffff8147e2f5)
Location: fs/fat/nfs.c:56
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8147e290-ffffffff8147e3be: __fat_nfs_get_inode (STB_LOCAL)
ffffffff81be0027-ffffffff81be0047: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (ffffffff814d5a95)
Location: fs/fat/nfs.c:56
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff814d5a30-ffffffff814d5b6b: __fat_nfs_get_inode (STB_LOCAL)
ffffffff81cd0732-ffffffff81cd076f: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (ffffffff81562c18)
Location: fs/fat/nfs.c:56
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81562bb0-ffffffff81562cdb: __fat_nfs_get_inode (STB_LOCAL)
ffffffff81e839b6-ffffffff81e839f3: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (ffffffff81605688)
Location: fs/fat/nfs.c:56
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81605620-ffffffff81605766: __fat_nfs_get_inode (STB_LOCAL)
ffffffff82072458-ffffffff82072475: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (ffffffff8163d598)
Location: fs/fat/nfs.c:56
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff8163d530-ffffffff8163d676: __fat_nfs_get_inode (STB_LOCAL)
ffffffff820f2073-ffffffff820f2090: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (ffffffff81676b08)
Location: fs/fat/nfs.c:56
Inline: True
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81676aa0-ffffffff81676be6: __fat_nfs_get_inode (STB_LOCAL)
ffffffff821cf355-ffffffff821cf372: __fat_nfs_get_inode.cold (STB_LOCAL)
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
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffff8000104ef600)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffff8000104ef600-ffff8000104ef764: __fat_nfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (c06ad33c)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
c06ad33c-c06ad4b4: __fat_nfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (c00000000062ec80)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
c00000000062ec80-c00000000062ee50: __fat_nfs_get_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/nfs.c (ffffffe00035f548)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffe00035f548-ffffffe00035f654: __fat_nfs_get_inode (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81406f60-ffffffff81407087: __fat_nfs_get_inode (STB_LOCAL)
ffffffff81407484-ffffffff814074a4: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff813f79e0-ffffffff813f7b07: __fat_nfs_get_inode (STB_LOCAL)
ffffffff813f7f04-ffffffff813f7f24: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff814042e0-ffffffff81404407: __fat_nfs_get_inode (STB_LOCAL)
ffffffff81404804-ffffffff81404824: __fat_nfs_get_inode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct inode *__fat_nfs_get_inode(struct super_block *sb, u64 ino, u32 generation, loff_t i_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/nfs.c (0)
Location: fs/fat/nfs.c:56
Inline: False
Direct callers:
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_nfs_get_inode
```
**Symbols:**

```
ffffffff81419f50-ffffffff8141a077: __fat_nfs_get_inode (STB_LOCAL)
ffffffff8141a484-ffffffff8141a4a4: __fat_nfs_get_inode.cold (STB_LOCAL)
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
