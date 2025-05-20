# Function: <code>ext4_fc_replay_inode</code>

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
int ext4_fc_replay_inode(struct super_block *sb, struct ext4_fc_tl *tl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81455240)
Location: fs/ext4/fast_commit.c:1458
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81455240-ffffffff81455537: ext4_fc_replay_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fc_replay_inode(struct super_block *sb, struct ext4_fc_tl *tl, u8 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145a980)
Location: fs/ext4/fast_commit.c:1455
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff8145a980-ffffffff8145ac68: ext4_fc_replay_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fc_replay_inode(struct super_block *sb, struct ext4_fc_tl *tl, u8 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814aeb30)
Location: fs/ext4/fast_commit.c:1431
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff814aeb30-ffffffff814aee35: ext4_fc_replay_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fc_replay_inode(struct super_block *sb, struct ext4_fc_tl *tl, u8 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815379f0)
Location: fs/ext4/fast_commit.c:1511
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815379f0-ffffffff81537d57: ext4_fc_replay_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fc_replay_inode(struct super_block *sb, struct ext4_fc_tl_mem *tl, u8 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d5bc0)
Location: fs/ext4/fast_commit.c:1517
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815d5bc0-ffffffff815d5f27: ext4_fc_replay_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fc_replay_inode(struct super_block *sb, struct ext4_fc_tl_mem *tl, u8 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160d780)
Location: fs/ext4/fast_commit.c:1517
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff8160d780-ffffffff8160dadc: ext4_fc_replay_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fc_replay_inode(struct super_block *sb, struct ext4_fc_tl_mem *tl, u8 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81646540)
Location: fs/ext4/fast_commit.c:1517
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81646540-ffffffff8164689c: ext4_fc_replay_inode (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *val</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ext4_fc_tl *tl</code> ➡️ <code>struct ext4_fc_tl_mem *tl</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
