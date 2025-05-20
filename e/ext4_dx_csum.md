# Function: <code>ext4_dx_csum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a1b10)
Location: fs/ext4/namei.c:417
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff812a1b10-ffffffff812a1bd7: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d0a40)
Location: fs/ext4/namei.c:417
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff812d0a40-ffffffff812d0b38: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e67c0)
Location: fs/ext4/namei.c:417
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff812e67c0-ffffffff812e68b8: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813163d0)
Location: fs/ext4/namei.c:417
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813163d0-ffffffff813164c0: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133ac40)
Location: fs/ext4/namei.c:418
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff8133ac40-ffffffff8133ad30: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81369210)
Location: fs/ext4/namei.c:419
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff81369210-ffffffff81369300: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813816b0)
Location: fs/ext4/namei.c:420
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813816b0-ffffffff813817a0: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aa950)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813aa950-ffffffff813aaa24: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c3880)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813c3880-ffffffff813c3954: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8140fed0)
Location: fs/ext4/namei.c:442
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_dx_csum_verify
```
**Symbols:**

```
ffffffff8140fed0-ffffffff8140ffa2: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814233a0)
Location: fs/ext4/namei.c:438
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_csum_set
  - fs/ext4/namei.c:ext4_dx_csum_verify
```
**Symbols:**

```
ffffffff814233a0-ffffffff81423472: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81429ba0)
Location: fs/ext4/namei.c:440
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff81429ba0-ffffffff81429c7c: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147d930)
Location: fs/ext4/namei.c:441
Inline: False
Direct callers:
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff8147d930-ffffffff8147da0c: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81500620)
Location: fs/ext4/namei.c:464
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff81500620-ffffffff81500755: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159b100)
Location: fs/ext4/namei.c:469
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff8159b100-ffffffff8159b235: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d1980)
Location: fs/ext4/namei.c:469
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff815d1980-ffffffff815d1ab5: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160a120)
Location: fs/ext4/namei.c:471
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_handle_dirty_dx_node
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff8160a120-ffffffff8160a255: ext4_dx_csum (STB_LOCAL)
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
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049b170)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffff80001049b170-ffff80001049b220: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065cc88)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
c065cc88-c065cd2c: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c5d30)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
c0000000005c5d30-c0000000005c5e70: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00031e7ac)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffe00031e7ac-ffffffe00031e87e: ext4_dx_csum (STB_LOCAL)
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
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bbe60)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813bbe60-ffffffff813bbf34: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ac8f0)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813ac8f0-ffffffff813ac9c4: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b9840)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813b9840-ffffffff813b9914: ext4_dx_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__le32 ext4_dx_csum(struct inode *inode, struct ext4_dir_entry *dirent, int count_offset, int count, struct dx_tail *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ce3e0)
Location: fs/ext4/namei.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_finish
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813ce3e0-ffffffff813ce4b4: ext4_dx_csum (STB_LOCAL)
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
