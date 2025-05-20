# Function: <code>ext4_dirent_csum_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirent_csum_verify(struct inode *inode, struct ext4_dir_entry *dirent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a1c20)
Location: fs/ext4/namei.c:343
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:__ext4_read_dirblock
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff812a1c20-ffffffff812a1d72: ext4_dirent_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirent_csum_verify(struct inode *inode, struct ext4_dir_entry *dirent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d0b80)
Location: fs/ext4/namei.c:343
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff812d0b80-ffffffff812d0cd8: ext4_dirent_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirent_csum_verify(struct inode *inode, struct ext4_dir_entry *dirent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e6900)
Location: fs/ext4/namei.c:343
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff812e6900-ffffffff812e6a52: ext4_dirent_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirent_csum_verify(struct inode *inode, struct ext4_dir_entry *dirent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81316500)
Location: fs/ext4/namei.c:343
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff81316500-ffffffff813165dc: ext4_dirent_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirent_csum_verify(struct inode *inode, struct ext4_dir_entry *dirent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133ad70)
Location: fs/ext4/namei.c:344
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff8133ad70-ffffffff8133ae4c: ext4_dirent_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirent_csum_verify(struct inode *inode, struct ext4_dir_entry *dirent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81369430)
Location: fs/ext4/namei.c:345
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff81369430-ffffffff81369510: ext4_dirent_csum_verify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_dirent_csum_verify(struct inode *inode, struct ext4_dir_entry *dirent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813818d0)
Location: fs/ext4/namei.c:346
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff813818d0-ffffffff813819b0: ext4_dirent_csum_verify (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
