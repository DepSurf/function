# Function: <code>ext4_fc_track_template</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_fc_track_template(handle_t *handle, struct inode *inode, int (*__fc_track_fn)(struct inode *, void *, bool), void *args, int enqueue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81456eaa)
Location: fs/ext4/fast_commit.c:379
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
```
**Symbols:**

```
ffffffff81455a50-ffffffff81455bac: ext4_fc_track_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_fc_track_template(handle_t *handle, struct inode *inode, int (*__fc_track_fn)(struct inode *, void *, bool), void *args, int enqueue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145c85a)
Location: fs/ext4/fast_commit.c:379
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
```
**Symbols:**

```
ffffffff8145b650-ffffffff8145b7ad: ext4_fc_track_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_fc_track_template(handle_t *handle, struct inode *inode, int (*__fc_track_fn)(struct inode *, void *, bool), void *args, int enqueue);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814b00b9)
Location: fs/ext4/fast_commit.c:345
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
```
**Symbols:**

```
ffffffff814aef20-ffffffff814af063: ext4_fc_track_template (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81538ab5)
Location: fs/ext4/fast_commit.c:371
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d6d84)
Location: fs/ext4/fast_commit.c:373
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160e954)
Location: fs/ext4/fast_commit.c:373
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81647714)
Location: fs/ext4/fast_commit.c:373
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
  - fs/ext4/fast_commit.c:ext4_fc_track_inode
  - fs/ext4/fast_commit.c:__ext4_fc_track_create
  - fs/ext4/fast_commit.c:__ext4_fc_track_link
  - fs/ext4/fast_commit.c:__ext4_fc_track_unlink
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
</ul>
