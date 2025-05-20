# Function: <code>ext4_insert_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_insert_dentry(struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a4dc0)
Location: fs/ext4/namei.c:1839
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff812a4dc0-ffffffff812a4e5b: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_insert_dentry(struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d3e40)
Location: fs/ext4/namei.c:1866
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff812d3e40-ffffffff812d3edb: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_insert_dentry(struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e9b80)
Location: fs/ext4/namei.c:1870
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff812e9b80-ffffffff812e9c1b: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81319310)
Location: fs/ext4/namei.c:1819
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff81319310-ffffffff813193aa: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133da50)
Location: fs/ext4/namei.c:1814
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff8133da50-ffffffff8133daea: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136bff0)
Location: fs/ext4/namei.c:1816
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff8136bff0-ffffffff8136c08a: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813844d0)
Location: fs/ext4/namei.c:1817
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff813844d0-ffffffff8138456a: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813addc0)
Location: fs/ext4/namei.c:1950
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff813addc0-ffffffff813ade66: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c6d00)
Location: fs/ext4/namei.c:1951
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff813c6d00-ffffffff813c6da6: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81413220)
Location: fs/ext4/namei.c:1967
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff81413220-ffffffff814132c7: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81426800)
Location: fs/ext4/namei.c:1957
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff81426800-ffffffff814268a7: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142d2a0)
Location: fs/ext4/namei.c:2053
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff8142d2a0-ffffffff8142d3b8: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814811b0)
Location: fs/ext4/namei.c:2056
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff814811b0-ffffffff814812cb: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81504160)
Location: fs/ext4/namei.c:2106
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff81504160-ffffffff81504292: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159ed30)
Location: fs/ext4/namei.c:2111
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff8159ed30-ffffffff8159ee62: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_insert_dentry(struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:2126
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff820efc51-ffffffff820efc6c: ext4_insert_dentry.cold (STB_LOCAL)
ffffffff815d5620-ffffffff815d57a7: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_insert_dentry(struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:2130
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff821ccd29-ffffffff821ccd44: ext4_insert_dentry.cold (STB_LOCAL)
ffffffff8160dcc0-ffffffff8160de47: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049e848)
Location: fs/ext4/namei.c:1951
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffff80001049e848-ffff80001049e924: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0660640)
Location: fs/ext4/namei.c:1951
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_add_dirent_to_inline
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
c0660640-c066070c: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005ca4c0)
Location: fs/ext4/namei.c:1951
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
c0000000005ca4c0-c0000000005ca620: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe0003211d2)
Location: fs/ext4/namei.c:1951
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffe0003211d2-ffffffe00032129a: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bf2e0)
Location: fs/ext4/namei.c:1951
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff813bf2e0-ffffffff813bf386: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813afd70)
Location: fs/ext4/namei.c:1951
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff813afd70-ffffffff813afe16: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bc7b0)
Location: fs/ext4/namei.c:1951
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff813bc7b0-ffffffff813bc856: ext4_insert_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_insert_dentry(struct inode *inode, struct ext4_dir_entry_2 *de, int buf_size, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d1870)
Location: fs/ext4/namei.c:1951
Inline: False
Direct callers:
  - fs/ext4/namei.c:add_dirent_to_buf
```
**Symbols:**

```
ffffffff813d1870-ffffffff813d1916: ext4_insert_dentry (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct inode *dir</code>
</li>
<li>
<b>Param reordered. </b>
<code>dir, inode, de, buf_size, fname</code> ➡️ <code>inode, de, buf_size, fname</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *dir</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, de, buf_size, fname</code> ➡️ <code>dir, inode, de, buf_size, fname</code>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
