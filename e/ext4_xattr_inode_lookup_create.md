# Function: <code>ext4_xattr_inode_lookup_create</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133b785)
Location: fs/ext4/xattr.c:1464
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/xattr.c (ffffffff8135fb83)
Location: fs/ext4/xattr.c:1485
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138ddb0)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff8138ddb0-ffffffff8138e3f7: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a6330)
Location: fs/ext4/xattr.c:1512
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813a6330-ffffffff813a69c0: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d0bd0)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813d0bd0-ffffffff813d123d: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ea2a0)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813ea2a0-ffffffff813ea91a: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81437580)
Location: fs/ext4/xattr.c:1497
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81437580-ffffffff81437719: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814500b0)
Location: fs/ext4/xattr.c:1502
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff814500b0-ffffffff81450249: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814558a0)
Location: fs/ext4/xattr.c:1502
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff814558a0-ffffffff81455b1e: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a98c0)
Location: fs/ext4/xattr.c:1506
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff814a98c0-ffffffff814a9b3e: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81531c00)
Location: fs/ext4/xattr.c:1515
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81531c00-ffffffff81531e9a: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815d01a0)
Location: fs/ext4/xattr.c:1541
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff815d01a0-ffffffff815d0349: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff816079c0)
Location: fs/ext4/xattr.c:1568
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff816079c0-ffffffff81607ba7: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81640700)
Location: fs/ext4/xattr.c:1568
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81640700-ffffffff816408e7: ext4_xattr_inode_lookup_create (STB_LOCAL)
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
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c2858)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffff8000104c2858-ffff8000104c2e8c: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0687388)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
c0687388-c06877d4: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fa750)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
c0000000005fa750-c0000000005fb000: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033e090)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffe00033e090-ffffffe00033e5ca: ext4_xattr_inode_lookup_create (STB_LOCAL)
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
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e2880)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813e2880-ffffffff813e2efa: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d3300)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813d3300-ffffffff813d397a: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813dfc00)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813dfc00-ffffffff813e027a: ext4_xattr_inode_lookup_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_xattr_inode_lookup_create(handle_t *handle, struct inode *inode, const void *value, size_t value_len, struct inode **ret_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f5020)
Location: fs/ext4/xattr.c:1513
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff813f5020-ffffffff813f569a: ext4_xattr_inode_lookup_create (STB_LOCAL)
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
