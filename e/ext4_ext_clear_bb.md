# Function: <code>ext4_ext_clear_bb</code>

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
int ext4_ext_clear_bb(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f8200)
Location: fs/ext4/extents.c:6014
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff813f8200-ffffffff813f8421: ext4_ext_clear_bb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_clear_bb(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fe680)
Location: fs/ext4/extents.c:6020
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff813fe680-ffffffff813fe8a1: ext4_ext_clear_bb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_clear_bb(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814509c0)
Location: fs/ext4/extents.c:6060
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff814509c0-ffffffff81450c2c: ext4_ext_clear_bb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_clear_bb(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814cd9c0)
Location: fs/ext4/extents.c:6073
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff814cd9c0-ffffffff814cdc56: ext4_ext_clear_bb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_clear_bb(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81566120)
Location: fs/ext4/extents.c:6075
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff81566120-ffffffff815663b6: ext4_ext_clear_bb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_clear_bb(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8159ddb0)
Location: fs/ext4/extents.c:6046
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff8159ddb0-ffffffff8159e046: ext4_ext_clear_bb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_clear_bb(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d6a00)
Location: fs/ext4/extents.c:6081
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_replay_inode
```
**Symbols:**

```
ffffffff815d6a00-ffffffff815d6c96: ext4_ext_clear_bb (STB_GLOBAL)
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
