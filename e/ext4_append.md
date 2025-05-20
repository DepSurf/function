# Function: <code>ext4_append</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a1910)
Location: fs/ext4/namei.c:50
Inline: False
Direct callers:
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_mkdir
```
**Symbols:**

```
ffffffff812a1910-ffffffff812a19e6: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d0840)
Location: fs/ext4/namei.c:50
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff812d0840-ffffffff812d0915: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e65e0)
Location: fs/ext4/namei.c:50
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff812e65e0-ffffffff812e66b5: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81316200)
Location: fs/ext4/namei.c:50
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81316200-ffffffff813162d5: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133aa70)
Location: fs/ext4/namei.c:51
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8133aa70-ffffffff8133ab45: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81368fd0)
Location: fs/ext4/namei.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81368fd0-ffffffff813690b2: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81381470)
Location: fs/ext4/namei.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81381470-ffffffff81381552: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aa720)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813aa720-ffffffff813aa7ff: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c3650)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813c3650-ffffffff813c372f: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8140fb00)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8140fb00-ffffffff8140fbdf: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81422fc0)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81422fc0-ffffffff8142309f: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81429840)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81429840-ffffffff8142991e: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8147d630-ffffffff8147d72e: ext4_append (STB_LOCAL)
ffffffff81cccbbc-ffffffff81cccbe2: ext4_append.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff815001b0-ffffffff81500351: ext4_append (STB_LOCAL)
ffffffff81e7fa9f-ffffffff81e7fac5: ext4_append.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8159a880-ffffffff8159aa3f: ext4_append (STB_LOCAL)
ffffffff8206ff8a-ffffffff8206ffb0: ext4_append.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff815d1120-ffffffff815d12df: ext4_append (STB_LOCAL)
ffffffff820efb2d-ffffffff820efb53: ext4_append.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_init_new_dir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff816098c0-ffffffff81609a7f: ext4_append (STB_LOCAL)
ffffffff821ccc05-ffffffff821ccc2b: ext4_append.cold (STB_LOCAL)
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
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049af58)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffff80001049af58-ffff80001049b054: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065ca58)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
c065ca58-c065cb68: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c59a0)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
c0000000005c59a0-c0000000005c5b04: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00031e56e)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffe00031e56e-ffffffe00031e642: ext4_append (STB_LOCAL)
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
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bbc30)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813bbc30-ffffffff813bbd0f: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ac6c0)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813ac6c0-ffffffff813ac79f: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b9520)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813b9520-ffffffff813b95ff: ext4_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_append(handle_t *handle, struct inode *inode, ext4_lblk_t *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ce1b0)
Location: fs/ext4/namei.c:53
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/namei.c:ext4_dx_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:make_indexed_dir
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff813ce1b0-ffffffff813ce28f: ext4_append (STB_LOCAL)
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
