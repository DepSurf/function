# Function: <code>ext4_xattr_move_to_block</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813245a2)
Location: fs/ext4/xattr.c:1345
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff8133e290)
Location: fs/ext4/xattr.c:2494
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff81362870)
Location: fs/ext4/xattr.c:2530
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff813911c6)
Location: fs/ext4/xattr.c:2546
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff813a9dc3)
Location: fs/ext4/xattr.c:2545
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d3670)
Location: fs/ext4/xattr.c:2546
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813d3670-ffffffff813d397d: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ecd50)
Location: fs/ext4/xattr.c:2546
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813ecd50-ffffffff813ed05d: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81439ba0)
Location: fs/ext4/xattr.c:2533
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_make_inode_space
```
**Symbols:**

```
ffffffff81439ba0-ffffffff81439ead: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814526b0)
Location: fs/ext4/xattr.c:2540
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_make_inode_space
```
**Symbols:**

```
ffffffff814526b0-ffffffff814529bd: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81458040)
Location: fs/ext4/xattr.c:2540
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff81458040-ffffffff81458350: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814ac1d0)
Location: fs/ext4/xattr.c:2523
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff814ac1d0-ffffffff814ac4e0: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81534150)
Location: fs/ext4/xattr.c:2538
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff81534150-ffffffff8153448b: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815d2640)
Location: fs/ext4/xattr.c:2558
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff815d2640-ffffffff815d2993: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8160a120)
Location: fs/ext4/xattr.c:2601
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff8160a120-ffffffff8160a4a5: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81642e70)
Location: fs/ext4/xattr.c:2601
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff81642e70-ffffffff81643253: ext4_xattr_move_to_block (STB_LOCAL)
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
In fs/ext4/xattr.c (ffff8000104c6700)
Location: fs/ext4/xattr.c:2546
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (c068a6c4)
Location: fs/ext4/xattr.c:2546
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fdcf0)
Location: fs/ext4/xattr.c:2546
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
c0000000005fdcf0-c0000000005fe078: ext4_xattr_move_to_block (STB_LOCAL)
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
In fs/ext4/xattr.c (ffffffe000340b38)
Location: fs/ext4/xattr.c:2546
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e5330)
Location: fs/ext4/xattr.c:2546
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813e5330-ffffffff813e563d: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d5db0)
Location: fs/ext4/xattr.c:2546
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813d5db0-ffffffff813d60bd: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e26b0)
Location: fs/ext4/xattr.c:2546
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813e26b0-ffffffff813e29bd: ext4_xattr_move_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_xattr_move_to_block(handle_t *handle, struct inode *inode, struct ext4_inode *raw_inode, struct ext4_xattr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f7ac0)
Location: fs/ext4/xattr.c:2546
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff813f7ac0-ffffffff813f7dcd: ext4_xattr_move_to_block (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
