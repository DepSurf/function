# Function: <code>ext4_read_inode_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812934b0)
Location: fs/ext4/ialloc.c:157
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_orphan_get
```
**Symbols:**

```
ffffffff812934b0-ffffffff81293bad: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812c0a70)
Location: fs/ext4/ialloc.c:157
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff812c0a70-ffffffff812c115b: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812d60a0)
Location: fs/ext4/ialloc.c:157
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff812d60a0-ffffffff812d678b: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812f4420)
Location: fs/ext4/ialloc.c:159
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff812f4420-ffffffff812f4a6b: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81318b60)
Location: fs/ext4/ialloc.c:160
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81318b60-ffffffff813191fc: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81346a10)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81346a10-ffffffff81347011: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8135ebc0)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8135ebc0-ffffffff8135f1c1: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81387e20)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81387e20-ffffffff813883b5: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813a07d0)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813a07d0-ffffffff813a0d7a: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ecb90)
Location: fs/ext4/ialloc.c:119
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813ecb90-ffffffff813ecfe9: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813fed90)
Location: fs/ext4/ialloc.c:124
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813fed90-ffffffff813ff1b6: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81404fa0)
Location: fs/ext4/ialloc.c:124
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81404fa0-ffffffff81405544: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:124
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff814577a0-ffffffff81457d74: ext4_read_inode_bitmap (STB_LOCAL)
ffffffff81cca2a6-ffffffff81cca2ca: ext4_read_inode_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (0)
Location: fs/ext4/ialloc.c:124
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff814d52c0-ffffffff814d5886: ext4_read_inode_bitmap (STB_LOCAL)
ffffffff81e7cfde-ffffffff81e7d002: ext4_read_inode_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8156e240)
Location: fs/ext4/ialloc.c:124
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8156e240-ffffffff8156e63f: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815a6100)
Location: fs/ext4/ialloc.c:124
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff815a6100-ffffffff815a64eb: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815def70)
Location: fs/ext4/ialloc.c:124
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_mark_inode_used
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff815def70-ffffffff815df36a: ext4_read_inode_bitmap (STB_LOCAL)
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
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffff800010473f60)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffff800010473f60-ffff80001047454c: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c0635368)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
c0635368-c0635ad4: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (c0000000005952a0)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
c0000000005952a0-c000000000595b18: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffe0002ff9da)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffe0002ff9da-ffffffe000300016: ext4_read_inode_bitmap (STB_LOCAL)
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
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81398db0)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81398db0-ffffffff8139935a: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81389840)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81389840-ffffffff81389dea: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81396610)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81396610-ffffffff81396bba: ext4_read_inode_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_read_inode_bitmap(struct super_block *sb, ext4_group_t block_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813aa870)
Location: fs/ext4/ialloc.c:118
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_orphan_get
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813aa870-ffffffff813aaea6: ext4_read_inode_bitmap (STB_LOCAL)
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
