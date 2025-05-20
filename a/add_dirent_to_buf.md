# Function: <code>add_dirent_to_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a4e60)
Location: fs/ext4/namei.c:1873
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff812a4e60-ffffffff812a5075: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d3ee0)
Location: fs/ext4/namei.c:1900
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff812d3ee0-ffffffff812d40f4: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e9c20)
Location: fs/ext4/namei.c:1904
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff812e9c20-ffffffff812e9e08: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813193b0)
Location: fs/ext4/namei.c:1851
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff813193b0-ffffffff8131954b: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133daf0)
Location: fs/ext4/namei.c:1846
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff8133daf0-ffffffff8133dc8b: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136c090)
Location: fs/ext4/namei.c:1848
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff8136c090-ffffffff8136c240: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81384570)
Location: fs/ext4/namei.c:1849
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff81384570-ffffffff81384720: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ade70)
Location: fs/ext4/namei.c:1982
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff813ade70-ffffffff813ae027: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c6db0)
Location: fs/ext4/namei.c:1983
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff813c6db0-ffffffff813c6f74: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814132d0)
Location: fs/ext4/namei.c:1999
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff814132d0-ffffffff814134bb: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814268b0)
Location: fs/ext4/namei.c:1989
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff814268b0-ffffffff81426aa8: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142d3c0)
Location: fs/ext4/namei.c:2093
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff8142d3c0-ffffffff8142d5bb: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814812d0)
Location: fs/ext4/namei.c:2096
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff814812d0-ffffffff814814d5: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815042a0)
Location: fs/ext4/namei.c:2146
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff815042a0-ffffffff815044bb: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159ee80)
Location: fs/ext4/namei.c:2151
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff8159ee80-ffffffff8159f05b: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d57c0)
Location: fs/ext4/namei.c:2166
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff815d57c0-ffffffff815d599b: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160de60)
Location: fs/ext4/namei.c:2170
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff8160de60-ffffffff8160e030: add_dirent_to_buf (STB_LOCAL)
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
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049e928)
Location: fs/ext4/namei.c:1983
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffff80001049e928-ffff80001049eb78: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c066070c)
Location: fs/ext4/namei.c:1983
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
c066070c-c06609b8: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005ca620)
Location: fs/ext4/namei.c:1983
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
c0000000005ca620-c0000000005ca918: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00032129a)
Location: fs/ext4/namei.c:1983
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffe00032129a-ffffffe00032141e: add_dirent_to_buf (STB_LOCAL)
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
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bf390)
Location: fs/ext4/namei.c:1983
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff813bf390-ffffffff813bf554: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813afe20)
Location: fs/ext4/namei.c:1983
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff813afe20-ffffffff813affe4: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bc860)
Location: fs/ext4/namei.c:1983
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff813bc860-ffffffff813bca24: add_dirent_to_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_dirent_to_buf(handle_t *handle, struct ext4_filename *fname, struct inode *dir, struct inode *inode, struct ext4_dir_entry_2 *de, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d1920)
Location: fs/ext4/namei.c:1983
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
```
**Symbols:**

```
ffffffff813d1920-ffffffff813d1ae4: add_dirent_to_buf (STB_LOCAL)
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
