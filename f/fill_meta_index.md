# Function: <code>fill_meta_index</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81322800)
Location: fs/squashfs/file.c:236
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff8133868d)
Location: fs/squashfs/file.c:236
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff8134d1f2)
Location: fs/squashfs/file.c:236
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813718a2)
Location: fs/squashfs/file.c:236
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813a026d)
Location: fs/squashfs/file.c:240
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (ffffffff813b8fef)
Location: fs/squashfs/file.c:240
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_readpage
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
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813e33e0-ffffffff813e39f0: fill_meta_index.constprop.0 (STB_LOCAL)
ffffffff813e3f2d-ffffffff813e3f5a: fill_meta_index.constprop.0.cold (STB_LOCAL)
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
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813fd410-ffffffff813fda20: fill_meta_index.constprop.0 (STB_LOCAL)
ffffffff813fdf7e-ffffffff813fdfab: fill_meta_index.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (ffffffff8144b080)
Location: fs/squashfs/file.c:227
Inline: True
```
**Symbols:**

```
ffffffff8144b080-ffffffff8144b371: fill_meta_index.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (ffffffff81467760)
Location: fs/squashfs/file.c:227
Inline: True
```
**Symbols:**

```
ffffffff81467760-ffffffff81467a51: fill_meta_index.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (ffffffff8146cd30)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8146cd30-ffffffff8146d159: fill_meta_index.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff814c35d0-ffffffff814c39d7: fill_meta_index.constprop.0 (STB_LOCAL)
ffffffff81ccefd7-ffffffff81cceff4: fill_meta_index.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_read_folio
```
**Symbols:**

```
ffffffff8154e1a0-ffffffff8154e5cd: fill_meta_index.constprop.0 (STB_LOCAL)
ffffffff81e8201f-ffffffff81e82054: fill_meta_index.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fill_meta_index(struct inode *inode, int index, u64 *index_block, int *index_offset, u64 *data_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:228
Inline: False
Direct callers:
  - fs/squashfs/file.c:read_blocklist
```
**Symbols:**

```
ffffffff815ee4f0-ffffffff815ee91e: fill_meta_index (STB_LOCAL)
ffffffff82071535-ffffffff8207156a: fill_meta_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fill_meta_index(struct inode *inode, int index, u64 *index_block, int *index_offset, u64 *data_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:228
Inline: False
Direct callers:
  - fs/squashfs/file.c:read_blocklist
```
**Symbols:**

```
ffffffff81626470-ffffffff81626910: fill_meta_index (STB_LOCAL)
ffffffff820f11e5-ffffffff820f120a: fill_meta_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fill_meta_index(struct inode *inode, int index, u64 *index_block, int *index_offset, u64 *data_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:228
Inline: False
Direct callers:
  - fs/squashfs/file.c:read_blocklist
```
**Symbols:**

```
ffffffff8165f5e0-ffffffff8165fa80: fill_meta_index (STB_LOCAL)
ffffffff821ce48d-ffffffff821ce4b2: fill_meta_index.cold (STB_LOCAL)
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
In fs/squashfs/file.c (ffff8000104db490)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffff8000104db490-ffff8000104dba60: fill_meta_index.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (c069cb7c)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
c069cb7c-c069d25c: fill_meta_index.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (c000000000616450)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
c000000000616450-c000000000616ba0: fill_meta_index.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (ffffffe000350210)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffe000350210-ffffffe000350774: fill_meta_index.constprop.0 (STB_LOCAL)
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
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813f59f0-ffffffff813f6000: fill_meta_index.constprop.0 (STB_LOCAL)
ffffffff813f655e-ffffffff813f658b: fill_meta_index.constprop.0.cold (STB_LOCAL)
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
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813e6470-ffffffff813e6a80: fill_meta_index.constprop.0 (STB_LOCAL)
ffffffff813e6fde-ffffffff813e700b: fill_meta_index.constprop.0.cold (STB_LOCAL)
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
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813f2d70-ffffffff813f3380: fill_meta_index.constprop.0 (STB_LOCAL)
ffffffff813f38de-ffffffff813f390b: fill_meta_index.constprop.0.cold (STB_LOCAL)
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
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:227
Inline: True
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81408960-ffffffff81408f70: fill_meta_index.constprop.0 (STB_LOCAL)
ffffffff8140950c-ffffffff81409539: fill_meta_index.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
