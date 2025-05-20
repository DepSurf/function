# Function: <code>ext4_used_dirs_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7d70)
Location: fs/ext4/super.c:271
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:ext4_free_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff812b7d70-ffffffff812b7d93: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e6a70)
Location: fs/ext4/super.c:300
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff812e6a70-ffffffff812e6a93: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fc620)
Location: fs/ext4/super.c:302
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff812fc620-ffffffff812fc643: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81331270)
Location: fs/ext4/super.c:304
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81331270-ffffffff81331293: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81355730)
Location: fs/ext4/super.c:304
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81355730-ffffffff81355753: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81383b60)
Location: fs/ext4/super.c:304
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81383b60-ffffffff81383b83: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139c640)
Location: fs/ext4/super.c:327
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8139c640-ffffffff8139c663: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c6890)
Location: fs/ext4/super.c:328
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813c6890-ffffffff813c68b3: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dfc50)
Location: fs/ext4/super.c:323
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813dfc50-ffffffff813dfc73: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142c510)
Location: fs/ext4/super.c:303
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8142c510-ffffffff8142c533: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81445330)
Location: fs/ext4/super.c:392
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81445330-ffffffff81445353: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144ac50)
Location: fs/ext4/super.c:392
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8144ac50-ffffffff8144ac73: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149eb60)
Location: fs/ext4/super.c:389
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff8149eb60-ffffffff8149eb83: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81525260)
Location: fs/ext4/super.c:408
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81525260-ffffffff8152528f: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c2810)
Location: fs/ext4/super.c:402
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff815c2810-ffffffff815c283f: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f9f90)
Location: fs/ext4/super.c:402
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff815f9f90-ffffffff815f9fbf: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81632b90)
Location: fs/ext4/super.c:410
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff81632b90-ffffffff81632bbf: ext4_used_dirs_set (STB_GLOBAL)
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
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b8bc0)
Location: fs/ext4/super.c:323
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffff8000104b8bc0-ffff8000104b8c10: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067c268)
Location: fs/ext4/super.c:323
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
c067c268-c067c298: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005edca0)
Location: fs/ext4/super.c:323
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
c0000000005edca0-c0000000005edcc8: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000335594)
Location: fs/ext4/super.c:323
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffe000335594-ffffffe0003355da: ext4_used_dirs_set (STB_GLOBAL)
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
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8230)
Location: fs/ext4/super.c:323
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813d8230-ffffffff813d8253: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c8cb0)
Location: fs/ext4/super.c:323
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813c8cb0-ffffffff813c8cd3: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d56c0)
Location: fs/ext4/super.c:323
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813d56c0-ffffffff813d56e3: ext4_used_dirs_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_used_dirs_set(struct super_block *sb, struct ext4_group_desc *bg, __u32 count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ea940)
Location: fs/ext4/super.c:323
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:ext4_free_inode
```
**Symbols:**

```
ffffffff813ea940-ffffffff813ea963: ext4_used_dirs_set (STB_GLOBAL)
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
