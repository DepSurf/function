# Function: <code>ext4_fc_track_unlink</code>

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
void ext4_fc_track_unlink(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81456cf0)
Location: fs/ext4/fast_commit.c:492
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_unlink
```
**Symbols:**

```
ffffffff81456cf0-ffffffff81456d07: ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_fc_track_unlink(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145c6a0)
Location: fs/ext4/fast_commit.c:492
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_unlink
```
**Symbols:**

```
ffffffff8145c6a0-ffffffff8145c6b7: ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_fc_track_unlink(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814aff10)
Location: fs/ext4/fast_commit.c:460
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_unlink
```
**Symbols:**

```
ffffffff814aff10-ffffffff814aff27: ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fc_track_unlink(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81538500)
Location: fs/ext4/fast_commit.c:493
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff81538500-ffffffff81538555: ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fc_track_unlink(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d6780)
Location: fs/ext4/fast_commit.c:504
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff815d6780-ffffffff815d67dc: ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fc_track_unlink(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160e350)
Location: fs/ext4/fast_commit.c:504
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff8160e350-ffffffff8160e3ac: ext4_fc_track_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fc_track_unlink(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81647110)
Location: fs/ext4/fast_commit.c:504
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff81647110-ffffffff8164716c: ext4_fc_track_unlink (STB_GLOBAL)
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
