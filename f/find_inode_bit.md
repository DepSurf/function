# Function: <code>find_inode_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81318420)
Location: fs/ext4/ialloc.c:741
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81318420-ffffffff81318577: find_inode_bit.isra.16 (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff81346860)
Location: fs/ext4/ialloc.c:711
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81346860-ffffffff813469bf: find_inode_bit.isra.19 (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff8135e550)
Location: fs/ext4/ialloc.c:711
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff8135e550-ffffffff8135e6a1: find_inode_bit.isra.20 (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff81387730)
Location: fs/ext4/ialloc.c:711
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81387730-ffffffff81387885: find_inode_bit.isra.0 (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff813a0620)
Location: fs/ext4/ialloc.c:709
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813a0620-ffffffff813a0775: find_inode_bit.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int find_inode_bit(struct super_block *sb, ext4_group_t group, struct buffer_head *bitmap, long unsigned int *ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ec060)
Location: fs/ext4/ialloc.c:711
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813ec060-ffffffff813ec10d: find_inode_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int find_inode_bit(struct super_block *sb, ext4_group_t group, struct buffer_head *bitmap, long unsigned int *ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813fe210)
Location: fs/ext4/ialloc.c:715
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813fe210-ffffffff813fe2bd: find_inode_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int find_inode_bit(struct super_block *sb, ext4_group_t group, struct buffer_head *bitmap, long unsigned int *ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81404630)
Location: fs/ext4/ialloc.c:716
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81404630-ffffffff814047aa: find_inode_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int find_inode_bit(struct super_block *sb, ext4_group_t group, struct buffer_head *bitmap, long unsigned int *ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81456de0)
Location: fs/ext4/ialloc.c:718
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81456de0-ffffffff81456f5a: find_inode_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int find_inode_bit(struct super_block *sb, ext4_group_t group, struct buffer_head *bitmap, long unsigned int *ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff814d48c0)
Location: fs/ext4/ialloc.c:718
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff814d48c0-ffffffff814d4a3f: find_inode_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int find_inode_bit(struct super_block *sb, ext4_group_t group, struct buffer_head *bitmap, long unsigned int *ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8156d580)
Location: fs/ext4/ialloc.c:717
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff8156d580-ffffffff8156d6eb: find_inode_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int find_inode_bit(struct super_block *sb, ext4_group_t group, struct buffer_head *bitmap, long unsigned int *ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815a5470)
Location: fs/ext4/ialloc.c:717
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff815a5470-ffffffff815a55db: find_inode_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int find_inode_bit(struct super_block *sb, ext4_group_t group, struct buffer_head *bitmap, long unsigned int *ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815de2e0)
Location: fs/ext4/ialloc.c:717
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff815de2e0-ffffffff815de44b: find_inode_bit (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffff800010473ab0)
Location: fs/ext4/ialloc.c:709
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffff800010473ab0-ffff800010473c1c: find_inode_bit.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int find_inode_bit(struct super_block *sb, ext4_group_t group, struct buffer_head *bitmap, long unsigned int *ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c0634b38)
Location: fs/ext4/ialloc.c:709
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
c0634b38-c0634c9c: find_inode_bit (STB_LOCAL)
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
In fs/ext4/ialloc.c (c000000000594ff0)
Location: fs/ext4/ialloc.c:709
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
c000000000594ff0-c0000000005951ec: find_inode_bit.isra.0 (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffe0002ff826)
Location: fs/ext4/ialloc.c:709
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffe0002ff826-ffffffe0002ff94a: find_inode_bit.isra.0 (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff81398c00)
Location: fs/ext4/ialloc.c:709
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81398c00-ffffffff81398d55: find_inode_bit.isra.0 (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff81389690)
Location: fs/ext4/ialloc.c:709
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81389690-ffffffff813897e5: find_inode_bit.isra.0 (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff81396460)
Location: fs/ext4/ialloc.c:709
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81396460-ffffffff813965b5: find_inode_bit.isra.0 (STB_LOCAL)
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
In fs/ext4/ialloc.c (ffffffff813aa6c0)
Location: fs/ext4/ialloc.c:709
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813aa6c0-ffffffff813aa815: find_inode_bit.isra.0 (STB_LOCAL)
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
