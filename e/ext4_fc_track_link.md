# Function: <code>ext4_fc_track_link</code>

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
void ext4_fc_track_link(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81456e50)
Location: fs/ext4/fast_commit.c:511
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_link
```
**Symbols:**

```
ffffffff81456e50-ffffffff81456e67: ext4_fc_track_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_fc_track_link(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145c800)
Location: fs/ext4/fast_commit.c:511
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_link
```
**Symbols:**

```
ffffffff8145c800-ffffffff8145c817: ext4_fc_track_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_fc_track_link(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814b0060)
Location: fs/ext4/fast_commit.c:479
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_link
```
**Symbols:**

```
ffffffff814b0060-ffffffff814b0077: ext4_fc_track_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fc_track_link(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81538670)
Location: fs/ext4/fast_commit.c:522
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_link
```
**Symbols:**

```
ffffffff81538670-ffffffff815386c5: ext4_fc_track_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fc_track_link(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d6910)
Location: fs/ext4/fast_commit.c:531
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_link
```
**Symbols:**

```
ffffffff815d6910-ffffffff815d696c: ext4_fc_track_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fc_track_link(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160e4e0)
Location: fs/ext4/fast_commit.c:531
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_link
```
**Symbols:**

```
ffffffff8160e4e0-ffffffff8160e53c: ext4_fc_track_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fc_track_link(handle_t *handle, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff816472a0)
Location: fs/ext4/fast_commit.c:531
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_link
```
**Symbols:**

```
ffffffff816472a0-ffffffff816472fc: ext4_fc_track_link (STB_GLOBAL)
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
