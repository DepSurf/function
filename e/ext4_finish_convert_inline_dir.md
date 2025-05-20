# Function: <code>ext4_finish_convert_inline_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812dff59)
Location: fs/ext4/inline.c:1110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8130fbff)
Location: fs/ext4/inline.c:1110
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81325a23)
Location: fs/ext4/inline.c:1128
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812f9a78)
Location: fs/ext4/inline.c:1130
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131e0b8)
Location: fs/ext4/inline.c:1121
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134c0b9)
Location: fs/ext4/inline.c:1124
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813641f9)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138dd4d)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a67ad)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_finish_convert_inline_dir(handle_t *handle, struct inode *inode, struct buffer_head *dir_block, void *buf, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f1960)
Location: fs/ext4/inline.c:1127
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff813f1960-ffffffff813f1aa8: ext4_finish_convert_inline_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_finish_convert_inline_dir(handle_t *handle, struct inode *inode, struct buffer_head *dir_block, void *buf, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81404000)
Location: fs/ext4/inline.c:1127
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff81404000-ffffffff81404148: ext4_finish_convert_inline_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_finish_convert_inline_dir(handle_t *handle, struct inode *inode, struct buffer_head *dir_block, void *buf, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140a4e0)
Location: fs/ext4/inline.c:1133
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff8140a4e0-ffffffff8140a626: ext4_finish_convert_inline_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_finish_convert_inline_dir(handle_t *handle, struct inode *inode, struct buffer_head *dir_block, void *buf, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145d0f0)
Location: fs/ext4/inline.c:1149
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff8145d0f0-ffffffff8145d236: ext4_finish_convert_inline_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_finish_convert_inline_dir(handle_t *handle, struct inode *inode, struct buffer_head *dir_block, void *buf, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814db910)
Location: fs/ext4/inline.c:1145
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff814db910-ffffffff814dba61: ext4_finish_convert_inline_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_finish_convert_inline_dir(handle_t *handle, struct inode *inode, struct buffer_head *dir_block, void *buf, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81574860)
Location: fs/ext4/inline.c:1144
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff81574860-ffffffff815749b9: ext4_finish_convert_inline_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_finish_convert_inline_dir(handle_t *handle, struct inode *inode, struct buffer_head *dir_block, void *buf, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815ac720)
Location: fs/ext4/inline.c:1126
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff815ac720-ffffffff815ac884: ext4_finish_convert_inline_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_finish_convert_inline_dir(handle_t *handle, struct inode *inode, struct buffer_head *dir_block, void *buf, int inline_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e54b0)
Location: fs/ext4/inline.c:1125
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
**Symbols:**

```
ffffffff815e54b0-ffffffff815e5614: ext4_finish_convert_inline_dir (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047a0d0)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063b930)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059c310)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000304316)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139ed8d)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138f81d)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139c5ed)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b0b00)
Location: fs/ext4/inline.c:1127
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
