# Function: <code>__xattr_check_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130c670)
Location: fs/ext4/xattr.c:235
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
```
**Symbols:**

```
ffffffff8130c670-ffffffff8130c6e6: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813225f0)
Location: fs/ext4/xattr.c:241
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_listxattr
```
**Symbols:**

```
ffffffff813225f0-ffffffff8132266a: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81339a70)
Location: fs/ext4/xattr.c:243
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff81339a70-ffffffff81339adb: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8135ddc0)
Location: fs/ext4/xattr.c:244
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff8135ddc0-ffffffff8135de2b: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138c6b0)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff8138c6b0-ffffffff8138c724: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a52e0)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813a52e0-ffffffff813a5354: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813cf500)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813cf500-ffffffff813cf57e: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e8bd0)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813e8bd0-ffffffff813e8c4e: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81435920)
Location: fs/ext4/xattr.c:263
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff81435920-ffffffff8143599f: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144e360)
Location: fs/ext4/xattr.c:263
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_xattr_ibody_list
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff8144e360-ffffffff8144e3df: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81453e70)
Location: fs/ext4/xattr.c:263
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff81453e70-ffffffff81453eef: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a7f10)
Location: fs/ext4/xattr.c:263
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff814a7f10-ffffffff814a7f8f: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8152f820)
Location: fs/ext4/xattr.c:263
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff8152f820-ffffffff8152f8af: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815cdaf0)
Location: fs/ext4/xattr.c:265
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff815cdaf0-ffffffff815cdb7f: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8160ae68)
Location: fs/ext4/xattr.c:312
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81643c28)
Location: fs/ext4/xattr.c:312
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
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
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c19c0)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffff8000104c19c0-ffff8000104c1a7c: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c068558c)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
c068558c-c068562c: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005f86c0)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
c0000000005f86c0-c0000000005f8788: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033ce78)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffe00033ce78-ffffffe00033cf02: __xattr_check_inode (STB_LOCAL)
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
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e11b0)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813e11b0-ffffffff813e122e: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d1c30)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813d1c30-ffffffff813d1cae: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813de530)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813de530-ffffffff813de5ae: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __xattr_check_inode(struct inode *inode, struct ext4_xattr_ibody_header *header, void *end, const char *function, unsigned int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f3950)
Location: fs/ext4/xattr.c:261
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_get_inode_usage
  - fs/ext4/xattr.c:ext4_listxattr
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813f3950-ffffffff813f39ce: __xattr_check_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
