# Function: <code>ext4_initialize_dirent_tail</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aaa30)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813aaa30-ffffffff813aaa70: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c3960)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813c3960-ffffffff813c39a0: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814101d0)
Location: fs/ext4/namei.c:303
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff814101d0-ffffffff81410210: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814236a0)
Location: fs/ext4/namei.c:299
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff814236a0-ffffffff814236e0: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81429dc0)
Location: fs/ext4/namei.c:301
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81429dc0-ffffffff81429e00: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147dd90)
Location: fs/ext4/namei.c:302
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8147dd90-ffffffff8147ddce: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81500950)
Location: fs/ext4/namei.c:325
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81500950-ffffffff8150099a: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159b460)
Location: fs/ext4/namei.c:330
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8159b460-ffffffff8159b4aa: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d1ce0)
Location: fs/ext4/namei.c:330
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff815d1ce0-ffffffff815d1d2a: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160a470)
Location: fs/ext4/namei.c:330
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8160a470-ffffffff8160a4ba: ext4_initialize_dirent_tail (STB_GLOBAL)
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
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049b328)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffff80001049b328-ffff80001049b390: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065ce18)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
c065ce18-c065ce70: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c5e70)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
c0000000005c5e70-c0000000005c5ed0: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00031e87e)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffe00031e87e-ffffffe00031e904: ext4_initialize_dirent_tail (STB_GLOBAL)
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
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bbf40)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813bbf40-ffffffff813bbf80: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ac9d0)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813ac9d0-ffffffff813aca10: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b9920)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813b9920-ffffffff813b9960: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_initialize_dirent_tail(struct buffer_head *bh, unsigned int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ce4c0)
Location: fs/ext4/namei.c:296
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813ce4c0-ffffffff813ce500: ext4_initialize_dirent_tail (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
