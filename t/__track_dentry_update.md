# Function: <code>__track_dentry_update</code>

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
int __track_dentry_update(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81456920)
Location: fs/ext4/fast_commit.c:428
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff81456920-ffffffff81456b28: __track_dentry_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __track_dentry_update(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145c2d0)
Location: fs/ext4/fast_commit.c:428
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff8145c2d0-ffffffff8145c4d8: __track_dentry_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __track_dentry_update(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814afbd0)
Location: fs/ext4/fast_commit.c:395
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff814afbd0-ffffffff814afdd3: __track_dentry_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __track_dentry_update(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81538180)
Location: fs/ext4/fast_commit.c:414
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff81538180-ffffffff815383ef: __track_dentry_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __track_dentry_update(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d63b0)
Location: fs/ext4/fast_commit.c:416
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff815d63b0-ffffffff815d6648: __track_dentry_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __track_dentry_update(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160df60)
Location: fs/ext4/fast_commit.c:416
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff8160df60-ffffffff8160e218: __track_dentry_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __track_dentry_update(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81646d20)
Location: fs/ext4/fast_commit.c:416
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
**Symbols:**

```
ffffffff81646d20-ffffffff81646fd8: __track_dentry_update (STB_LOCAL)
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
