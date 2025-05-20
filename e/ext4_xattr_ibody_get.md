# Function: <code>ext4_xattr_ibody_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812de000)
Location: fs/ext4/xattr.c:326
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
**Symbols:**

```
ffffffff812de000-ffffffff812de14e: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130dc30)
Location: fs/ext4/xattr.c:346
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
```
**Symbols:**

```
ffffffff8130dc30-ffffffff8130dd75: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813239b0)
Location: fs/ext4/xattr.c:351
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
```
**Symbols:**

```
ffffffff813239b0-ffffffff81323af5: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133ce70)
Location: fs/ext4/xattr.c:537
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff8133ce70-ffffffff8133cfcf: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81361450)
Location: fs/ext4/xattr.c:547
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff81361450-ffffffff813615af: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138fc00)
Location: fs/ext4/xattr.c:573
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff8138fc00-ffffffff8138fd76: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a8850)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813a8850-ffffffff813a89c6: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d2a50)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813d2a50-ffffffff813d2bd6: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ec130)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813ec130-ffffffff813ec2b6: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81439440)
Location: fs/ext4/xattr.c:574
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff81439440-ffffffff814395c6: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81451f60)
Location: fs/ext4/xattr.c:574
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff81451f60-ffffffff814520e6: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81457690)
Location: fs/ext4/xattr.c:574
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff81457690-ffffffff81457822: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814ab770)
Location: fs/ext4/xattr.c:574
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff814ab770-ffffffff814ab902: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815335c0)
Location: fs/ext4/xattr.c:589
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff815335c0-ffffffff81533778: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815d1b80)
Location: fs/ext4/xattr.c:605
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff815d1b80-ffffffff815d1d38: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81609620)
Location: fs/ext4/xattr.c:634
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff81609620-ffffffff816097de: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81642370)
Location: fs/ext4/xattr.c:634
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff81642370-ffffffff8164252e: ext4_xattr_ibody_get (STB_GLOBAL)
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
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c5008)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffff8000104c5008-ffff8000104c51c4: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c06890e8)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
c06890e8-c0689284: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fcc20)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
c0000000005fcc20-c0000000005fce74: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033f934)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffe00033f934-ffffffe00033fa74: ext4_xattr_ibody_get (STB_GLOBAL)
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
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e4710)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813e4710-ffffffff813e4896: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d5190)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813d5190-ffffffff813d5316: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e1a90)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813e1a90-ffffffff813e1c16: ext4_xattr_ibody_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_xattr_ibody_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f6ea0)
Location: fs/ext4/xattr.c:572
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
  - fs/ext4/inline.c:ext4_update_inline_data
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff813f6ea0-ffffffff813f7026: ext4_xattr_ibody_get (STB_GLOBAL)
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
