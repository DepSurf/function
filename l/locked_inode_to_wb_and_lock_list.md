# Function: <code>locked_inode_to_wb_and_lock_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81238150)
Location: fs/fs-writeback.c:268
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff81238150-ffffffff81238214: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81262170)
Location: fs/fs-writeback.c:268
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff81262170-ffffffff81262278: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81275670)
Location: fs/fs-writeback.c:268
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff81275670-ffffffff81275778: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81282a40)
Location: fs/fs-writeback.c:282
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff81282a40-ffffffff81282b4f: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a5580)
Location: fs/fs-writeback.c:282
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff812a5580-ffffffff812a569b: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812cbc50)
Location: fs/fs-writeback.c:282
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff812cbc50-ffffffff812cbd5a: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e1370)
Location: fs/fs-writeback.c:282
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff812e1370-ffffffff812e14a5: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812ffac0)
Location: fs/fs-writeback.c:284
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff812ffac0-ffffffff812ffc01: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813120d0)
Location: fs/fs-writeback.c:289
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff813120d0-ffffffff81312211: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134c1f0)
Location: fs/fs-writeback.c:290
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff8134c1f0-ffffffff8134c331: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813591c0)
Location: fs/fs-writeback.c:290
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff813591c0-ffffffff81359324: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135fd10)
Location: fs/fs-writeback.c:290
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff8135fd10-ffffffff8135fe74: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813ae940)
Location: fs/fs-writeback.c:300
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff813ae940-ffffffff813aeaa4: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81432bd0)
Location: fs/fs-writeback.c:301
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff81432bd0-ffffffff81432d3f: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c0b90)
Location: fs/fs-writeback.c:303
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff814c0b90-ffffffff814c0cff: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f5580)
Location: fs/fs-writeback.c:303
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff814f5580-ffffffff814f56ef: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81529c90)
Location: fs/fs-writeback.c:303
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff81529c90-ffffffff81529dff: locked_inode_to_wb_and_lock_list (STB_LOCAL)
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
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c7c58)
Location: fs/fs-writeback.c:289
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffff8000103c7c58-ffff8000103c7ec4: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a4ae4)
Location: fs/fs-writeback.c:289
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
c05a4ae4-c05a4d3c: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c8c80)
Location: fs/fs-writeback.c:289
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
c0000000004c8c80-c0000000004c8f20: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000285fd0)
Location: fs/fs-writeback.c:289
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffe000285fd0-ffffffe000286186: locked_inode_to_wb_and_lock_list (STB_LOCAL)
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
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130a6b0)
Location: fs/fs-writeback.c:289
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff8130a6b0-ffffffff8130a7f1: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fb2d0)
Location: fs/fs-writeback.c:289
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff812fb2d0-ffffffff812fb411: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813084a0)
Location: fs/fs-writeback.c:289
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff813084a0-ffffffff813085e1: locked_inode_to_wb_and_lock_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bdi_writeback *locked_inode_to_wb_and_lock_list(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81319ad0)
Location: fs/fs-writeback.c:289
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff81319ad0-ffffffff81319c65: locked_inode_to_wb_and_lock_list (STB_LOCAL)
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
