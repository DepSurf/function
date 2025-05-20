# Function: <code>ext4_get_journal_inode</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fd550)
Location: fs/ext4/super.c:4360
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff812fd550-ffffffff812fd60b: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813321f0)
Location: fs/ext4/super.c:4468
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813321f0-ffffffff813322ab: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813566e0)
Location: fs/ext4/super.c:4477
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813566e0-ffffffff8135679b: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813849f0)
Location: fs/ext4/super.c:4588
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813849f0-ffffffff81384aab: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139d4d0)
Location: fs/ext4/super.c:4651
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff8139d4d0-ffffffff8139d59d: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c7710)
Location: fs/ext4/super.c:4741
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813c7710-ffffffff813c77e6: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e0ad0)
Location: fs/ext4/super.c:4772
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813e0ad0-ffffffff813e0ba6: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142e340)
Location: fs/ext4/super.c:4933
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff8142e340-ffffffff8142e410: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81447020)
Location: fs/ext4/super.c:5219
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff81447020-ffffffff814470f0: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144c8c0)
Location: fs/ext4/super.c:5265
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff8144c8c0-ffffffff8144c987: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a0950)
Location: fs/ext4/super.c:5120
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff814a0950-ffffffff814a0a17: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81527410)
Location: fs/ext4/super.c:5566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff81527410-ffffffff815274e0: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c54e0)
Location: fs/ext4/super.c:5718
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff815c54e0-ffffffff815c55aa: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fd100)
Location: fs/ext4/super.c:5762
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff815fd100-ffffffff815fd1ca: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81635c20)
Location: fs/ext4/super.c:5769
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff81635c20-ffffffff81635d19: ext4_get_journal_inode (STB_LOCAL)
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
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b9e30)
Location: fs/ext4/super.c:4772
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffff8000104b9e30-ffff8000104b9f2c: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067d4b0)
Location: fs/ext4/super.c:4772
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
c067d4b0-c067d5a4: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005ef3e0)
Location: fs/ext4/super.c:4772
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
c0000000005ef3e0-c0000000005ef534: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe0003363d4)
Location: fs/ext4/super.c:4772
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffe0003363d4-ffffffe0003364c4: ext4_get_journal_inode (STB_LOCAL)
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
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d90b0)
Location: fs/ext4/super.c:4772
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813d90b0-ffffffff813d9186: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c9b30)
Location: fs/ext4/super.c:4772
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813c9b30-ffffffff813c9c06: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d6540)
Location: fs/ext4/super.c:4772
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813d6540-ffffffff813d6616: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct inode *ext4_get_journal_inode(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813eb7f0)
Location: fs/ext4/super.c:4772
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff813eb7f0-ffffffff813eb8c6: ext4_get_journal_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
