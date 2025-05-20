# Function: <code>ext4_ext_replay_shrink_inode</code>

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
void ext4_ext_replay_shrink_inode(struct inode *inode, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f7c00)
Location: fs/ext4/extents.c:5872
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_del_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
  - fs/ext4/fast_commit.c:ext4_fc_replay_add_range
```
**Symbols:**

```
ffffffff813f7c00-ffffffff813f7da5: ext4_ext_replay_shrink_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_ext_replay_shrink_inode(struct inode *inode, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fe090)
Location: fs/ext4/extents.c:5878
Inline: False
```
**Symbols:**

```
ffffffff813fe090-ffffffff813fe235: ext4_ext_replay_shrink_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_ext_replay_shrink_inode(struct inode *inode, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81450390)
Location: fs/ext4/extents.c:5909
Inline: False
```
**Symbols:**

```
ffffffff81450390-ffffffff81450535: ext4_ext_replay_shrink_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_ext_replay_shrink_inode(struct inode *inode, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814cd340)
Location: fs/ext4/extents.c:5922
Inline: False
```
**Symbols:**

```
ffffffff814cd340-ffffffff814cd505: ext4_ext_replay_shrink_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_ext_replay_shrink_inode(struct inode *inode, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81565a90)
Location: fs/ext4/extents.c:5934
Inline: False
```
**Symbols:**

```
ffffffff81565a90-ffffffff81565c55: ext4_ext_replay_shrink_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_ext_replay_shrink_inode(struct inode *inode, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8159d720)
Location: fs/ext4/extents.c:5905
Inline: False
```
**Symbols:**

```
ffffffff8159d720-ffffffff8159d8e5: ext4_ext_replay_shrink_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_ext_replay_shrink_inode(struct inode *inode, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d6370)
Location: fs/ext4/extents.c:5940
Inline: False
```
**Symbols:**

```
ffffffff815d6370-ffffffff815d6535: ext4_ext_replay_shrink_inode (STB_GLOBAL)
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
