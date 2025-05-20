# Function: <code>ext4_find_inline_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812e1fc0)
Location: fs/ext4/inline.c:1610
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff812e1fc0-ffffffff812e2129: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81311f60)
Location: fs/ext4/inline.c:1609
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81311f60-ffffffff813120c5: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81327ea0)
Location: fs/ext4/inline.c:1626
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81327ea0-ffffffff81328005: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fbda0)
Location: fs/ext4/inline.c:1628
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff812fbda0-ffffffff812fbf12: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813204f0)
Location: fs/ext4/inline.c:1619
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813204f0-ffffffff81320662: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134e660)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff8134e660-ffffffff8134e7d0: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813667e0)
Location: fs/ext4/inline.c:1625
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813667e0-ffffffff81366950: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138fb90)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8138fb90-ffffffff8138fce6: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a85f0)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813a85f0-ffffffff813a8746: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f4680)
Location: fs/ext4/inline.c:1624
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813f4680-ffffffff813f47fa: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81406e10)
Location: fs/ext4/inline.c:1624
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff81406e10-ffffffff81406f69: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140d280)
Location: fs/ext4/inline.c:1635
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8140d280-ffffffff8140d3d9: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814600f0)
Location: fs/ext4/inline.c:1652
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff814600f0-ffffffff81460257: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814de9b0)
Location: fs/ext4/inline.c:1677
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff814de9b0-ffffffff814deb37: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81577a60)
Location: fs/ext4/inline.c:1676
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff81577a60-ffffffff81577be7: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815aef70)
Location: fs/ext4/inline.c:1659
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff815aef70-ffffffff815af0fa: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e7d30)
Location: fs/ext4/inline.c:1658
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff815e7d30-ffffffff815e7eba: ext4_find_inline_entry (STB_GLOBAL)
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
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047be50)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffff80001047be50-ffff80001047bfcc: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063d864)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
c063d864-c063d9e8: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059f5e0)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
c00000000059f5e0-c00000000059f7a0: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe0003060a8)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffe0003060a8-ffffffe0003061ce: ext4_find_inline_entry (STB_GLOBAL)
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
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a0bd0)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813a0bd0-ffffffff813a0d26: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81391660)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff81391660-ffffffff813917b6: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139e430)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8139e430-ffffffff8139e586: ext4_find_inline_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_find_inline_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *has_inline_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b29a0)
Location: fs/ext4/inline.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813b29a0-ffffffff813b2af6: ext4_find_inline_entry (STB_GLOBAL)
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
<code>dir, fname, d_name, res_dir, has_inline_data</code> ➡️ <code>dir, fname, res_dir, has_inline_data</code>
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
