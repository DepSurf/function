# Function: <code>ext4_search_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, const struct qstr *d_name, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a3bc0)
Location: fs/ext4/namei.c:1265
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
```
**Symbols:**

```
ffffffff812a3bc0-ffffffff812a3d11: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, const struct qstr *d_name, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d2b50)
Location: fs/ext4/namei.c:1274
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
```
**Symbols:**

```
ffffffff812d2b50-ffffffff812d2c8c: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, const struct qstr *d_name, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e88a0)
Location: fs/ext4/namei.c:1276
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
```
**Symbols:**

```
ffffffff812e88a0-ffffffff812e89dc: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813180c0)
Location: fs/ext4/namei.c:1276
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813180c0-ffffffff813181fe: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133c920)
Location: fs/ext4/namei.c:1277
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff8133c920-ffffffff8133ca5e: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136ae60)
Location: fs/ext4/namei.c:1278
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff8136ae60-ffffffff8136af9e: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81383320)
Location: fs/ext4/namei.c:1279
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81383320-ffffffff8138345e: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aca70)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813aca70-ffffffff813acc62: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c59b0)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813c59b0-ffffffff813c5ba2: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81411df0)
Location: fs/ext4/namei.c:1382
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff81411df0-ffffffff81411fd8: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81425290)
Location: fs/ext4/namei.c:1371
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff81425290-ffffffff81425471: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142bfa0)
Location: fs/ext4/namei.c:1458
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8142bfa0-ffffffff8142c081: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147fe40)
Location: fs/ext4/namei.c:1459
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8147fe40-ffffffff8147ff21: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81502d00)
Location: fs/ext4/namei.c:1505
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff81502d00-ffffffff81502e23: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159d820)
Location: fs/ext4/namei.c:1510
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8159d820-ffffffff8159d943: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d4080)
Location: fs/ext4/namei.c:1526
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff815d4080-ffffffff815d41a7: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160c730)
Location: fs/ext4/namei.c:1530
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8160c730-ffffffff8160c857: ext4_search_dir (STB_GLOBAL)
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
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049d478)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffff80001049d478-ffff80001049d6a8: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065f108)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
c065f108-c065f350: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c8980)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
c0000000005c8980-c0000000005c8c94: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000320248)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffe000320248-ffffffe0003203da: ext4_search_dir (STB_GLOBAL)
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
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bdf90)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813bdf90-ffffffff813be182: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aea20)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813aea20-ffffffff813aec12: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bb650)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813bb650-ffffffff813bb78e: ext4_search_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_search_dir(struct buffer_head *bh, char *search_buf, int buf_size, struct inode *dir, struct ext4_filename *fname, unsigned int offset, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d0520)
Location: fs/ext4/namei.c:1378
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813d0520-ffffffff813d0712: ext4_search_dir (STB_GLOBAL)
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
<code>const struct qstr *d_name</code>
</li>
<li>
<b>Param reordered. </b>
<code>bh, search_buf, buf_size, dir, fname, d_name, offset, res_dir</code> ➡️ <code>bh, search_buf, buf_size, dir, fname, offset, res_dir</code>
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
