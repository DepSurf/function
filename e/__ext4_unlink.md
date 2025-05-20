# Function: <code>__ext4_unlink</code>

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
int __ext4_unlink(handle_t *handle, struct inode *dir, const struct qstr *d_name, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142a6a0)
Location: fs/ext4/namei.c:3189
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay_unlink
```
**Symbols:**

```
ffffffff8142a6a0-ffffffff8142a8e4: __ext4_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_unlink(handle_t *handle, struct inode *dir, const struct qstr *d_name, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814313c0)
Location: fs/ext4/namei.c:3319
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff814313c0-ffffffff81431604: __ext4_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_unlink(handle_t *handle, struct inode *dir, const struct qstr *d_name, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81484bd0)
Location: fs/ext4/namei.c:3147
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81484bd0-ffffffff81484e14: __ext4_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_unlink(handle_t *handle, struct inode *dir, const struct qstr *d_name, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81507e50)
Location: fs/ext4/namei.c:3194
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81507e50-ffffffff81508108: __ext4_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_unlink(struct inode *dir, const struct qstr *d_name, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815a28f0)
Location: fs/ext4/namei.c:3207
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815a28f0-ffffffff815a2c51: __ext4_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_unlink(struct inode *dir, const struct qstr *d_name, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d92d0)
Location: fs/ext4/namei.c:3228
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815d92d0-ffffffff815d9631: __ext4_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_unlink(struct inode *dir, const struct qstr *d_name, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff816119a0)
Location: fs/ext4/namei.c:3230
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff816119a0-ffffffff81611ceb: __ext4_unlink (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>handle_t *handle</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, dir, d_name, inode</code> ➡️ <code>dir, d_name, inode, dentry</code>
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
