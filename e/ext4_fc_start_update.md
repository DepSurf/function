# Function: <code>ext4_fc_start_update</code>

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
void ext4_fc_start_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81456750)
Location: fs/ext4/fast_commit.c:250
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff81456750-ffffffff814567e0: ext4_fc_start_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_fc_start_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145c100)
Location: fs/ext4/fast_commit.c:250
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_fileattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff8145c100-ffffffff8145c190: ext4_fc_start_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_fc_start_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814af970)
Location: fs/ext4/fast_commit.c:240
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/ioctl.c:ext4_compat_ioctl
  - fs/ext4/ioctl.c:ext4_fileattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff814af970-ffffffff814af9fd: ext4_fc_start_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fc_start_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81537dd0)
Location: fs/ext4/fast_commit.c:239
Inline: False
```
**Symbols:**

```
ffffffff81537dd0-ffffffff81537e63: ext4_fc_start_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fc_start_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d5fc0)
Location: fs/ext4/fast_commit.c:245
Inline: False
```
**Symbols:**

```
ffffffff815d5fc0-ffffffff815d6053: ext4_fc_start_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fc_start_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160db70)
Location: fs/ext4/fast_commit.c:245
Inline: False
```
**Symbols:**

```
ffffffff8160db70-ffffffff8160dc03: ext4_fc_start_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fc_start_update(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81646930)
Location: fs/ext4/fast_commit.c:245
Inline: False
```
**Symbols:**

```
ffffffff81646930-ffffffff816469c3: ext4_fc_start_update (STB_GLOBAL)
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
