# Function: <code>ext4_xattr_inode_write</code>

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
In fs/ext4/xattr.c (ffffffff8133b9e2)
Location: fs/ext4/xattr.c:1300
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
In fs/ext4/xattr.c (ffffffff8135fe08)
Location: fs/ext4/xattr.c:1321
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/xattr.c (ffffffff8138e015)
Location: fs/ext4/xattr.c:1349
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/xattr.c (ffffffff813a65b1)
Location: fs/ext4/xattr.c:1341
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/xattr.c (ffffffff813d0e06)
Location: fs/ext4/xattr.c:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/xattr.c (ffffffff813ea4d6)
Location: fs/ext4/xattr.c:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_inode_write(handle_t *handle, struct inode *ea_inode, const void *buf, int bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814365f0)
Location: fs/ext4/xattr.c:1324
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff814365f0-ffffffff814368b6: ext4_xattr_inode_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_inode_write(handle_t *handle, struct inode *ea_inode, const void *buf, int bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144f010)
Location: fs/ext4/xattr.c:1327
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8144f010-ffffffff8144f2d6: ext4_xattr_inode_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_inode_write(handle_t *handle, struct inode *ea_inode, const void *buf, int bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814548d0)
Location: fs/ext4/xattr.c:1327
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff814548d0-ffffffff81454b96: ext4_xattr_inode_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_write(handle_t *handle, struct inode *ea_inode, const void *buf, int bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1330
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff814a89e0-ffffffff814a8cbc: ext4_xattr_inode_write (STB_LOCAL)
ffffffff81cce0a0-ffffffff81cce0c1: ext4_xattr_inode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_write(handle_t *handle, struct inode *ea_inode, const void *buf, int bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1339
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8152ff60-ffffffff81530260: ext4_xattr_inode_write (STB_LOCAL)
ffffffff81e80fa2-ffffffff81e80fc8: ext4_xattr_inode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_write(handle_t *handle, struct inode *ea_inode, const void *buf, int bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1355
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff815ce960-ffffffff815cec65: ext4_xattr_inode_write (STB_LOCAL)
ffffffff82070ed5-ffffffff82070efb: ext4_xattr_inode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_write(handle_t *handle, struct inode *ea_inode, const void *buf, int bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1383
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81606230-ffffffff81606544: ext4_xattr_inode_write (STB_LOCAL)
ffffffff820f0bbd-ffffffff820f0be1: ext4_xattr_inode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_write(handle_t *handle, struct inode *ea_inode, const void *buf, int bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:1383
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff8163ef70-ffffffff8163f284: ext4_xattr_inode_write (STB_LOCAL)
ffffffff821cdd74-ffffffff821cdd98: ext4_xattr_inode_write.cold (STB_LOCAL)
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
In fs/ext4/xattr.c (ffff8000104c2a64)
Location: fs/ext4/xattr.c:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_xattr_inode_write(handle_t *handle, struct inode *ea_inode, const void *buf, int bufsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0685de4)
Location: fs/ext4/xattr.c:1342
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
c0685de4-c0686144: ext4_xattr_inode_write (STB_LOCAL)
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
In fs/ext4/xattr.c (c0000000005faa30)
Location: fs/ext4/xattr.c:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/xattr.c (ffffffe00033e268)
Location: fs/ext4/xattr.c:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/xattr.c (ffffffff813e2ab6)
Location: fs/ext4/xattr.c:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/xattr.c (ffffffff813d3536)
Location: fs/ext4/xattr.c:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/xattr.c (ffffffff813dfe36)
Location: fs/ext4/xattr.c:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/xattr.c (ffffffff813f5256)
Location: fs/ext4/xattr.c:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
<b>Arch</b>
<ul>
</ul>
