# Function: <code>ext4_sb_bread_unmovable</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_sb_bread_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144c279)
Location: fs/ext4/super.c:240
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81444fe0-ffffffff81445003: ext4_sb_bread_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_sb_bread_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81451b8e)
Location: fs/ext4/super.c:240
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8144a900-ffffffff8144a923: ext4_sb_bread_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_sb_bread_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a5205)
Location: fs/ext4/super.c:237
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8149e3b0-ffffffff8149e3d3: ext4_sb_bread_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_sb_bread_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8152d17b)
Location: fs/ext4/super.c:256
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff815249d0-ffffffff81524a02: ext4_sb_bread_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_sb_bread_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c4f0f)
Location: fs/ext4/super.c:249
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff815c1e60-ffffffff815c1e92: ext4_sb_bread_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_sb_bread_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fc5ff)
Location: fs/ext4/super.c:249
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_group_desc_init
```
**Symbols:**

```
ffffffff815f95e0-ffffffff815f9612: ext4_sb_bread_unmovable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_sb_bread_unmovable(struct super_block *sb, sector_t block);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81639f13)
Location: fs/ext4/super.c:253
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_group_desc_init
Direct callers:
  - fs/ext4/super.c:ext4_load_super
  - fs/ext4/super.c:ext4_load_super
```
**Symbols:**

```
ffffffff81632180-ffffffff81632218: ext4_sb_bread_unmovable (STB_GLOBAL)
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
