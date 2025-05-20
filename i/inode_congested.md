# Function: <code>inode_congested</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81237130)
Location: fs/fs-writeback.c:726
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff81237130-ffffffff81237239: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81260690)
Location: fs/fs-writeback.c:726
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/fadvise.c:SyS_fadvise64
```
**Symbols:**

```
ffffffff81260690-ffffffff812607a0: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81273b90)
Location: fs/fs-writeback.c:726
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/fadvise.c:SyS_fadvise64
```
**Symbols:**

```
ffffffff81273b90-ffffffff81273ca0: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81282220)
Location: fs/fs-writeback.c:740
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/fadvise.c:SyS_fadvise64
```
**Symbols:**

```
ffffffff81282220-ffffffff8128232d: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a4c30)
Location: fs/fs-writeback.c:740
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/fadvise.c:SyS_fadvise64
```
**Symbols:**

```
ffffffff812a4c30-ffffffff812a4d43: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812c9ee0)
Location: fs/fs-writeback.c:740
Inline: True
Direct callers:
  - mm/vmscan.c:shrink_page_list
  - mm/fadvise.c:ksys_fadvise64_64
```
**Symbols:**

```
ffffffff812c9ee0-ffffffff812ca019: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812df0a0)
Location: fs/fs-writeback.c:763
Inline: True
Direct callers:
  - mm/fadvise.c:vfs_fadvise
  - mm/vmscan.c:shrink_page_list
```
**Symbols:**

```
ffffffff812df0a0-ffffffff812df1d9: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd750)
Location: fs/fs-writeback.c:774
Inline: True
Direct callers:
  - mm/fadvise.c:vfs_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff812fd750-ffffffff812fd889: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130fba0)
Location: fs/fs-writeback.c:779
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff8130fba0-ffffffff8130fcd9: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81349400)
Location: fs/fs-writeback.c:780
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81349400-ffffffff81349526: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81356210)
Location: fs/fs-writeback.c:780
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81356210-ffffffff813562e2: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135ce00)
Location: fs/fs-writeback.c:786
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff8135ce00-ffffffff8135ced2: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813ab1e0)
Location: fs/fs-writeback.c:910
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:pageout
```
**Symbols:**

```
ffffffff813ab1e0-ffffffff813ab2b9: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c3760)
Location: fs/fs-writeback.c:779
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffff8000103c3760-ffff8000103c38e0: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a1b04)
Location: fs/fs-writeback.c:779
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
c05a1b04-c05a1c3c: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c54a0)
Location: fs/fs-writeback.c:779
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
c0000000004c54a0-c0000000004c56b8: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000284360)
Location: fs/fs-writeback.c:779
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffe000284360-ffffffe000284464: inode_congested (STB_GLOBAL)
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
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81308180)
Location: fs/fs-writeback.c:779
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81308180-ffffffff813082b9: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812f8da0)
Location: fs/fs-writeback.c:779
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff812f8da0-ffffffff812f8ed9: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81305f70)
Location: fs/fs-writeback.c:779
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff81305f70-ffffffff813060a9: inode_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int inode_congested(struct inode *inode, int cong_bits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813174d0)
Location: fs/fs-writeback.c:779
Inline: True
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - mm/vmscan.c:shrink_page_list
  - mm/swap_state.c:swap_cluster_readahead
```
**Symbols:**

```
ffffffff813174d0-ffffffff813175fc: inode_congested (STB_GLOBAL)
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
