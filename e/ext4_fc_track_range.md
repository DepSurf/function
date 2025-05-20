# Function: <code>ext4_fc_track_range</code>

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
void ext4_fc_track_range(handle_t *handle, struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81457070)
Location: fs/ext4/fast_commit.c:595
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81457070-ffffffff8145711b: ext4_fc_track_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_fc_track_range(handle_t *handle, struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145ca20)
Location: fs/ext4/fast_commit.c:595
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8145ca20-ffffffff8145cacb: ext4_fc_track_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_fc_track_range(handle_t *handle, struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814b0270)
Location: fs/ext4/fast_commit.c:563
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff814b0270-ffffffff814b0318: ext4_fc_track_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fc_track_range(handle_t *handle, struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81538a10)
Location: fs/ext4/fast_commit.c:634
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81538a10-ffffffff81538bd5: ext4_fc_track_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fc_track_range(handle_t *handle, struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d6ce0)
Location: fs/ext4/fast_commit.c:637
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff815d6ce0-ffffffff815d6e9f: ext4_fc_track_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fc_track_range(handle_t *handle, struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160e8b0)
Location: fs/ext4/fast_commit.c:637
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8160e8b0-ffffffff8160ea6f: ext4_fc_track_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fc_track_range(handle_t *handle, struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81647670)
Location: fs/ext4/fast_commit.c:637
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81647670-ffffffff8164782f: ext4_fc_track_range (STB_GLOBAL)
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
