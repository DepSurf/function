# Function: <code>__ext4_get_inode_loc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812962d0)
Location: fs/ext4/inode.c:3882
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_reserve_inode_write
```
**Symbols:**

```
ffffffff812962d0-ffffffff8129668c: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c38c0)
Location: fs/ext4/inode.c:4190
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff812c38c0-ffffffff812c3cbc: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812d8f70)
Location: fs/ext4/inode.c:4319
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff812d8f70-ffffffff812d936c: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812ff640)
Location: fs/ext4/inode.c:4443
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff812ff640-ffffffff812ffa42: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81323df0)
Location: fs/ext4/inode.c:4492
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff81323df0-ffffffff813241f5: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813507d0)
Location: fs/ext4/inode.c:4540
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff813507d0-ffffffff81350bb5: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81369c60)
Location: fs/ext4/inode.c:4570
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81369c60-ffffffff8136a045: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813930c0)
Location: fs/ext4/inode.c:4582
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813930c0-ffffffff813934b5: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813aba20)
Location: fs/ext4/inode.c:4568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813aba20-ffffffff813abe67: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f7d60)
Location: fs/ext4/inode.c:4265
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813f7d60-ffffffff813f81ba: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc, int in_mem, ext4_fsblk_t *ret_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81409a60)
Location: fs/ext4/inode.c:4302
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_fc_inode_loc
  - fs/ext4/inode.c:ext4_get_inode_loc
```
**Symbols:**

```
ffffffff81409a60-ffffffff81409e58: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc, int in_mem, ext4_fsblk_t *ret_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140fc10)
Location: fs/ext4/inode.c:4301
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_get_fc_inode_loc
  - fs/ext4/inode.c:ext4_get_inode_loc
```
**Symbols:**

```
ffffffff8140fc10-ffffffff8141002c: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc, int in_mem, ext4_fsblk_t *ret_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81462ce0)
Location: fs/ext4/inode.c:4224
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_get_fc_inode_loc
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
```
**Symbols:**

```
ffffffff81462ce0-ffffffff814630dc: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct super_block *sb, long unsigned int ino, struct inode *inode, struct ext4_iloc *iloc, ext4_fsblk_t *ret_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e27c0)
Location: fs/ext4/inode.c:4441
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_get_fc_inode_loc
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
```
**Symbols:**

```
ffffffff814e27c0-ffffffff814e2c21: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct super_block *sb, long unsigned int ino, struct inode *inode, struct ext4_iloc *iloc, ext4_fsblk_t *ret_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157bbc0)
Location: fs/ext4/inode.c:4528
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_get_fc_inode_loc
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
```
**Symbols:**

```
ffffffff8157bbc0-ffffffff8157c09e: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct super_block *sb, long unsigned int ino, struct inode *inode, struct ext4_iloc *iloc, ext4_fsblk_t *ret_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b2fc0)
Location: fs/ext4/inode.c:4313
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_get_fc_inode_loc
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
```
**Symbols:**

```
ffffffff815b2fc0-ffffffff815b34a1: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct super_block *sb, long unsigned int ino, struct inode *inode, struct ext4_iloc *iloc, ext4_fsblk_t *ret_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ebdb0)
Location: fs/ext4/inode.c:4332
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_get_fc_inode_loc
  - fs/ext4/inode.c:ext4_get_inode_loc
  - fs/ext4/inode.c:__ext4_get_inode_loc_noinmem
```
**Symbols:**

```
ffffffff815ebdb0-ffffffff815ec2b1: __ext4_get_inode_loc (STB_LOCAL)
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
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010480278)
Location: fs/ext4/inode.c:4568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffff800010480278-ffff8000104806f4: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c064163c)
Location: fs/ext4/inode.c:4568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
c064163c-c0641bcc: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a4830)
Location: fs/ext4/inode.c:4568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
c0000000005a4830-c0000000005a4e28: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000309016)
Location: fs/ext4/inode.c:4568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffe000309016-ffffffe000309390: __ext4_get_inode_loc (STB_LOCAL)
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
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4000)
Location: fs/ext4/inode.c:4568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813a4000-ffffffff813a4447: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394a90)
Location: fs/ext4/inode.c:4568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81394a90-ffffffff81394ed7: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a1860)
Location: fs/ext4/inode.c:4568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813a1860-ffffffff813a1ca7: __ext4_get_inode_loc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ext4_get_inode_loc(struct inode *inode, struct ext4_iloc *iloc, int in_mem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b6470)
Location: fs/ext4/inode.c:4568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_reserve_inode_write
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813b6470-ffffffff813b68f8: __ext4_get_inode_loc (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct super_block *sb</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int ino</code>
</li>
<li>
<b>Param added. </b>
<code>ext4_fsblk_t *ret_block</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, iloc, in_mem</code> ➡️ <code>sb, ino, iloc, in_mem, ret_block</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>int in_mem</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, ino, iloc, in_mem, ret_block</code> ➡️ <code>sb, ino, inode, iloc, ret_block</code>
</li>
</ul>
</details>
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
