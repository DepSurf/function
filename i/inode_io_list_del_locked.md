# Function: <code>inode_io_list_del_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81236620)
Location: fs/fs-writeback.c:159
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
```
**Symbols:**

```
ffffffff81236620-ffffffff81236669: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8125fcc0)
Location: fs/fs-writeback.c:159
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff8125fcc0-ffffffff8125fd09: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812731e0)
Location: fs/fs-writeback.c:159
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812731e0-ffffffff81273229: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812805f0)
Location: fs/fs-writeback.c:159
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812805f0-ffffffff81280639: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a3120)
Location: fs/fs-writeback.c:159
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812a3120-ffffffff812a3169: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812c9b70)
Location: fs/fs-writeback.c:159
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812c9b70-ffffffff812c9bb9: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812deda0)
Location: fs/fs-writeback.c:159
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812deda0-ffffffff812dede9: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd460)
Location: fs/fs-writeback.c:160
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812fd460-ffffffff812fd4a6: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130f950)
Location: fs/fs-writeback.c:143
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff8130f950-ffffffff8130f996: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81349050)
Location: fs/fs-writeback.c:142
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81349050-ffffffff813490dd: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81355fb0)
Location: fs/fs-writeback.c:142
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81355fb0-ffffffff8135603d: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135cb90)
Location: fs/fs-writeback.c:142
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff8135cb90-ffffffff8135cc24: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c72a8)
Location: fs/fs-writeback.c:143
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffff8000103c72a8-ffff8000103c72fc: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a15f0)
Location: fs/fs-writeback.c:143
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
c05a15f0-c05a1644: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c4ef0)
Location: fs/fs-writeback.c:143
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
c0000000004c4ef0-c0000000004c4f3c: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000284058)
Location: fs/fs-writeback.c:143
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffe000284058-ffffffe0002840a2: inode_io_list_del_locked (STB_LOCAL)
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
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81307f30)
Location: fs/fs-writeback.c:143
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81307f30-ffffffff81307f76: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812f8b50)
Location: fs/fs-writeback.c:143
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812f8b50-ffffffff812f8b96: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81305d20)
Location: fs/fs-writeback.c:143
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81305d20-ffffffff81305d66: inode_io_list_del_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void inode_io_list_del_locked(struct inode *inode, struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81317260)
Location: fs/fs-writeback.c:143
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:inode_io_list_del
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81317260-ffffffff813172a6: inode_io_list_del_locked (STB_LOCAL)
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
