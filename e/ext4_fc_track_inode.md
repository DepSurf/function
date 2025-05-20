# Function: <code>ext4_fc_track_inode</code>

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
void ext4_fc_track_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81456fd0)
Location: fs/ext4/fast_commit.c:546
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff81456fd0-ffffffff8145706a: ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_fc_track_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145c980)
Location: fs/ext4/fast_commit.c:546
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff8145c980-ffffffff8145ca1a: ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_fc_track_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814b01d0)
Location: fs/ext4/fast_commit.c:514
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff814b01d0-ffffffff814b026a: ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fc_track_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81538840)
Location: fs/ext4/fast_commit.c:577
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff81538840-ffffffff81538a03: ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fc_track_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d6b10)
Location: fs/ext4/fast_commit.c:582
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff815d6b10-ffffffff815d6ccc: ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fc_track_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160e6e0)
Location: fs/ext4/fast_commit.c:582
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff8160e6e0-ffffffff8160e89c: ext4_fc_track_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fc_track_inode(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff816474a0)
Location: fs/ext4/fast_commit.c:582
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
**Symbols:**

```
ffffffff816474a0-ffffffff8164765c: ext4_fc_track_inode (STB_GLOBAL)
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
