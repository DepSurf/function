# Function: <code>xattr_find_entry</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138c730)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff8138c730-ffffffff8138c834: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a5360)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813a5360-ffffffff813a5464: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813cf580)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813cf580-ffffffff813cf6a5: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e8c50)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813e8c50-ffffffff813e8d75: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81435aa0)
Location: fs/ext4/xattr.c:283
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff81435aa0-ffffffff81435bcb: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144e4e0)
Location: fs/ext4/xattr.c:283
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff8144e4e0-ffffffff8144e60b: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81453ff0)
Location: fs/ext4/xattr.c:283
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff81453ff0-ffffffff8145411b: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a8090)
Location: fs/ext4/xattr.c:283
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff814a8090-ffffffff814a81bb: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8152f9e0)
Location: fs/ext4/xattr.c:283
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff8152f9e0-ffffffff8152fb2a: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815cdcd0)
Location: fs/ext4/xattr.c:285
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff815cdcd0-ffffffff815cde1a: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff816055c0)
Location: fs/ext4/xattr.c:323
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff816055c0-ffffffff81605712: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8163e280)
Location: fs/ext4/xattr.c:323
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_ibody_find
  - fs/ext4/xattr.c:ext4_xattr_block_find
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
  - fs/ext4/xattr.c:ext4_xattr_block_get
```
**Symbols:**

```
ffffffff8163e280-ffffffff8163e3d2: xattr_find_entry (STB_LOCAL)
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
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c1a80)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffff8000104c1a80-ffff8000104c1bf8: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c068568c)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
c068568c-c06857e0: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005f8790)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
c0000000005f8790-c0000000005f895c: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033cffc)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffe00033cffc-ffffffe00033d102: xattr_find_entry (STB_LOCAL)
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
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e1230)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813e1230-ffffffff813e1355: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d1cb0)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813d1cb0-ffffffff813d1dd5: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813de5b0)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813de5b0-ffffffff813de6d5: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xattr_find_entry(struct inode *inode, struct ext4_xattr_entry **pentry, void *end, int name_index, const char *name, int sorted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f39d0)
Location: fs/ext4/xattr.c:281
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
  - fs/ext4/xattr.c:ext4_xattr_ibody_get
```
**Symbols:**

```
ffffffff813f39d0-ffffffff813f3af5: xattr_find_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
