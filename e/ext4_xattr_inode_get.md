# Function: <code>ext4_xattr_inode_get</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133abe0)
Location: fs/ext4/xattr.c:426
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff8133abe0-ffffffff8133adde: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8135f240)
Location: fs/ext4/xattr.c:445
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff8135f240-ffffffff8135f421: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138dbc0)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff8138dbc0-ffffffff8138dda1: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a8510)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813a8510-ffffffff813a86f1: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d09f0)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813d09f0-ffffffff813d0bc8: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ea0c0)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813ea0c0-ffffffff813ea298: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81436a30)
Location: fs/ext4/xattr.c:468
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff81436a30-ffffffff81436c0f: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144f460)
Location: fs/ext4/xattr.c:468
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff8144f460-ffffffff8144f63f: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81454eb0)
Location: fs/ext4/xattr.c:468
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff81454eb0-ffffffff81455082: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a8fd0)
Location: fs/ext4/xattr.c:468
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff814a8fd0-ffffffff814a91a2: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815309d0)
Location: fs/ext4/xattr.c:483
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff815309d0-ffffffff81530bb6: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:499
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff815cefb0-ffffffff815cf1ed: ext4_xattr_inode_get (STB_LOCAL)
ffffffff82070f9c-ffffffff82070fb1: ext4_xattr_inode_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:528
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff81606890-ffffffff81606acd: ext4_xattr_inode_get (STB_LOCAL)
ffffffff820f0c74-ffffffff820f0c89: ext4_xattr_inode_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:528
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff8163f5d0-ffffffff8163f80d: ext4_xattr_inode_get (STB_LOCAL)
ffffffff821cde2b-ffffffff821cde40: ext4_xattr_inode_get.cold (STB_LOCAL)
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
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c31e0)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffff8000104c31e0-ffff8000104c33ac: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c068711c)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
c068711c-c0687388: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fa4f0)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
c0000000005fa4f0-c0000000005fa744: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033d64c)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffe00033d64c-ffffffe00033d7ec: ext4_xattr_inode_get (STB_LOCAL)
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
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e26a0)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813e26a0-ffffffff813e2878: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d3120)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813d3120-ffffffff813d32f8: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813dfa20)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813dfa20-ffffffff813dfbf8: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_xattr_inode_get(struct inode *inode, struct ext4_xattr_entry *entry, void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f4e40)
Location: fs/ext4/xattr.c:466
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813f4e40-ffffffff813f5018: ext4_xattr_inode_get (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
