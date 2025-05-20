# Function: <code>ext4_get_fc_inode_loc</code>

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
int ext4_get_fc_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140cbf0)
Location: fs/ext4/inode.c:4468
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff8140cbf0-ffffffff8140cc05: ext4_get_fc_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_get_fc_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412d70)
Location: fs/ext4/inode.c:4467
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff81412d70-ffffffff81412d85: ext4_get_fc_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_get_fc_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814660a0)
Location: fs/ext4/inode.c:4388
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff814660a0-ffffffff814660b5: ext4_get_fc_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_get_fc_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e5b50)
Location: fs/ext4/inode.c:4609
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff814e5b50-ffffffff814e5b77: ext4_get_fc_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_get_fc_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157f2a0)
Location: fs/ext4/inode.c:4704
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff8157f2a0-ffffffff8157f2c7: ext4_get_fc_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_get_fc_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b6750)
Location: fs/ext4/inode.c:4489
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff815b6750-ffffffff815b6777: ext4_get_fc_inode_loc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_get_fc_inode_loc(struct super_block *sb, long unsigned int ino, struct ext4_iloc *iloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ef4f0)
Location: fs/ext4/inode.c:4508
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff815ef4f0-ffffffff815ef517: ext4_get_fc_inode_loc (STB_GLOBAL)
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
