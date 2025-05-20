# Function: <code>__ext4_fc_track_unlink</code>

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
void __ext4_fc_track_unlink(handle_t *handle, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81456bb0)
Location: fs/ext4/fast_commit.c:478
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff81456bb0-ffffffff81456cf0: __ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ext4_fc_track_unlink(handle_t *handle, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145c560)
Location: fs/ext4/fast_commit.c:478
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff8145c560-ffffffff8145c69f: __ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ext4_fc_track_unlink(handle_t *handle, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814afde0)
Location: fs/ext4/fast_commit.c:446
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff814afde0-ffffffff814aff02: __ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ext4_fc_track_unlink(handle_t *handle, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815383f0)
Location: fs/ext4/fast_commit.c:479
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff815383f0-ffffffff815384fb: __ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ext4_fc_track_unlink(handle_t *handle, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d6660)
Location: fs/ext4/fast_commit.c:490
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff815d6660-ffffffff815d676b: __ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ext4_fc_track_unlink(handle_t *handle, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160e230)
Location: fs/ext4/fast_commit.c:490
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff8160e230-ffffffff8160e33b: __ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ext4_fc_track_unlink(handle_t *handle, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81646ff0)
Location: fs/ext4/fast_commit.c:490
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/fast_commit.c:ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff81646ff0-ffffffff816470fb: __ext4_fc_track_unlink (STB_GLOBAL)
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
