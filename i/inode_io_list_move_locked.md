# Function: <code>inode_io_list_move_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81236670)
Location: fs/fs-writeback.c:135
Inline: True
Direct callers:
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
```
**Symbols:**

```
ffffffff81236670-ffffffff812366e2: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8125fd10)
Location: fs/fs-writeback.c:135
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff8125fd10-ffffffff8125fd82: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81273230)
Location: fs/fs-writeback.c:135
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81273230-ffffffff812732a2: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81280640)
Location: fs/fs-writeback.c:135
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81280640-ffffffff812806b2: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a3170)
Location: fs/fs-writeback.c:135
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812a3170-ffffffff812a31e2: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812c9bc0)
Location: fs/fs-writeback.c:135
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812c9bc0-ffffffff812c9c32: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812dedf0)
Location: fs/fs-writeback.c:135
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812dedf0-ffffffff812dee62: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd4b0)
Location: fs/fs-writeback.c:136
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812fd4b0-ffffffff812fd525: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130f9a0)
Location: fs/fs-writeback.c:119
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff8130f9a0-ffffffff8130fa15: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81348f30)
Location: fs/fs-writeback.c:118
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81348f30-ffffffff81348fe5: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81355e90)
Location: fs/fs-writeback.c:118
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81355e90-ffffffff81355f45: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135ca70)
Location: fs/fs-writeback.c:118
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff8135ca70-ffffffff8135cb28: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813aba9c)
Location: fs/fs-writeback.c:118
Inline: True
Inline callers:
  - fs/fs-writeback.c:redirty_tail_locked
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:inode_do_switch_wbs
```
**Symbols:**

```
ffffffff813aaf90-ffffffff813ab002: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814338bc)
Location: fs/fs-writeback.c:118
Inline: True
Inline callers:
  - fs/fs-writeback.c:redirty_tail_locked
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:inode_do_switch_wbs
```
**Symbols:**

```
ffffffff81431d90-ffffffff81431e2b: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814bf630)
Location: fs/fs-writeback.c:118
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_do_switch_wbs
```
**Symbols:**

```
ffffffff814bf630-ffffffff814bf6d0: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f4730)
Location: fs/fs-writeback.c:118
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_do_switch_wbs
```
**Symbols:**

```
ffffffff814f4730-ffffffff814f47d0: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81528e40)
Location: fs/fs-writeback.c:118
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:redirty_tail_locked
  - fs/fs-writeback.c:inode_do_switch_wbs
```
**Symbols:**

```
ffffffff81528e40-ffffffff81528ee0: inode_io_list_move_locked (STB_LOCAL)
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
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103c7300)
Location: fs/fs-writeback.c:119
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffff8000103c7300-ffff8000103c73b4: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a1808)
Location: fs/fs-writeback.c:119
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
c05a1808-c05a1898: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004c4fc0)
Location: fs/fs-writeback.c:119
Inline: False
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
c0000000004c4fc0-c0000000004c5074: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe0002840a2)
Location: fs/fs-writeback.c:119
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffe0002840a2-ffffffe00028413a: inode_io_list_move_locked (STB_LOCAL)
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
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81307f80)
Location: fs/fs-writeback.c:119
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81307f80-ffffffff81307ff5: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812f8ba0)
Location: fs/fs-writeback.c:119
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff812f8ba0-ffffffff812f8c15: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81305d70)
Location: fs/fs-writeback.c:119
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81305d70-ffffffff81305de5: inode_io_list_move_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool inode_io_list_move_locked(struct inode *inode, struct bdi_writeback *wb, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813172b0)
Location: fs/fs-writeback.c:119
Inline: True
Direct callers:
  - fs/fs-writeback.c:__mark_inode_dirty
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:redirty_tail
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff813172b0-ffffffff81317325: inode_io_list_move_locked (STB_LOCAL)
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
