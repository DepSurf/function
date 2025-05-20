# Function: <code>ext4_sb_breadahead_unmovable</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_sb_breadahead_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81445010)
Location: fs/ext4/super.c:246
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81445010-ffffffff81445052: ext4_sb_breadahead_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_sb_breadahead_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144a930)
Location: fs/ext4/super.c:246
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8144a930-ffffffff8144a974: ext4_sb_breadahead_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_sb_breadahead_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149e3e0)
Location: fs/ext4/super.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8149e3e0-ffffffff8149e424: ext4_sb_breadahead_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_sb_breadahead_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81524a10)
Location: fs/ext4/super.c:262
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff81524a10-ffffffff81524a61: ext4_sb_breadahead_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_sb_breadahead_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c1eb0)
Location: fs/ext4/super.c:255
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff815c1eb0-ffffffff815c1f0b: ext4_sb_breadahead_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_sb_breadahead_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f9630)
Location: fs/ext4/super.c:255
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff815f9630-ffffffff815f968b: ext4_sb_breadahead_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_sb_breadahead_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81632230)
Location: fs/ext4/super.c:262
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_get_inode_loc
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff81632230-ffffffff8163228e: ext4_sb_breadahead_unmovable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
