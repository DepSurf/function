# Function: <code>ext4_generic_delete_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a6720)
Location: fs/ext4/namei.c:2300
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/inline.c:ext4_delete_inline_entry
```
**Symbols:**

```
ffffffff812a6720-ffffffff812a6836: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d5790)
Location: fs/ext4/namei.c:2324
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/inline.c:ext4_delete_inline_entry
```
**Symbols:**

```
ffffffff812d5790-ffffffff812d58a5: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812eb490)
Location: fs/ext4/namei.c:2326
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_delete_entry
  - fs/ext4/inline.c:ext4_delete_inline_entry
```
**Symbols:**

```
ffffffff812eb490-ffffffff812eb5a5: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8131b130)
Location: fs/ext4/namei.c:2302
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff8131b130-ffffffff8131b252: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133f850)
Location: fs/ext4/namei.c:2297
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff8133f850-ffffffff8133f972: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136d770)
Location: fs/ext4/namei.c:2299
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff8136d770-ffffffff8136d89b: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81385bf0)
Location: fs/ext4/namei.c:2300
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff81385bf0-ffffffff81385d1b: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813afbd0)
Location: fs/ext4/namei.c:2440
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff813afbd0-ffffffff813afcfb: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c8b90)
Location: fs/ext4/namei.c:2448
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff813c8b90-ffffffff813c8cbb: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81414640)
Location: fs/ext4/namei.c:2468
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff81414640-ffffffff8141477f: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_generic_delete_entry(struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81427c90)
Location: fs/ext4/namei.c:2456
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff81427c90-ffffffff81427dcf: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_generic_delete_entry(struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142e8f0)
Location: fs/ext4/namei.c:2570
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff8142e8f0-ffffffff8142ea5d: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_generic_delete_entry(struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81483090)
Location: fs/ext4/namei.c:2577
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff81483090-ffffffff814831fa: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_generic_delete_entry(struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815060c0)
Location: fs/ext4/namei.c:2627
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff815060c0-ffffffff81506232: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_generic_delete_entry(struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815a0b80)
Location: fs/ext4/namei.c:2640
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff815a0b80-ffffffff815a0ccf: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_generic_delete_entry(struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d74f0)
Location: fs/ext4/namei.c:2660
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff815d74f0-ffffffff815d7642: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_generic_delete_entry(struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160fb60)
Location: fs/ext4/namei.c:2661
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff8160fb60-ffffffff8160fcb2: ext4_generic_delete_entry (STB_GLOBAL)
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
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff8000104a05a0)
Location: fs/ext4/namei.c:2448
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffff8000104a05a0-ffff8000104a0704: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c06626d0)
Location: fs/ext4/namei.c:2448
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
c06626d0-c0662844: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005cc8e0)
Location: fs/ext4/namei.c:2448
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
c0000000005cc8e0-c0000000005ccb94: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00032290a)
Location: fs/ext4/namei.c:2448
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffe00032290a-ffffffe000322a20: ext4_generic_delete_entry (STB_GLOBAL)
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
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c1170)
Location: fs/ext4/namei.c:2448
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff813c1170-ffffffff813c129b: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b1c00)
Location: fs/ext4/namei.c:2448
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff813b1c00-ffffffff813b1d2b: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813be620)
Location: fs/ext4/namei.c:2448
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff813be620-ffffffff813be74b: ext4_generic_delete_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_generic_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh, void *entry_buf, int buf_size, int csum_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d3700)
Location: fs/ext4/namei.c:2448
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/namei.c:ext4_delete_entry
```
**Symbols:**

```
ffffffff813d3700-ffffffff813d382b: ext4_generic_delete_entry (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>handle_t *handle</code>
</li>
<li>
<b>Param reordered. </b>
<code>handle, dir, de_del, bh, entry_buf, buf_size, csum_size</code> ➡️ <code>dir, de_del, bh, entry_buf, buf_size, csum_size</code>
</li>
</ul>
</details>
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
