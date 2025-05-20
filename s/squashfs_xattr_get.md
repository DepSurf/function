# Function: <code>squashfs_xattr_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (ffffffff813257f9)
Location: fs/squashfs/xattr.c:118
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff8133b5a9)
Location: fs/squashfs/xattr.c:118
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff813500d9)
Location: fs/squashfs/xattr.c:118
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff81374869)
Location: fs/squashfs/xattr.c:118
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff813a32b0)
Location: fs/squashfs/xattr.c:118
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff813bc0b0)
Location: fs/squashfs/xattr.c:118
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff813e6961)
Location: fs/squashfs/xattr.c:105
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff814009e1)
Location: fs/squashfs/xattr.c:105
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int squashfs_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (ffffffff8144e3b0)
Location: fs/squashfs/xattr.c:105
Inline: False
Direct callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
**Symbols:**

```
ffffffff8144e3b0-ffffffff8144e63e: squashfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int squashfs_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (ffffffff8146a910)
Location: fs/squashfs/xattr.c:105
Inline: False
Direct callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
**Symbols:**

```
ffffffff8146a910-ffffffff8146ab9e: squashfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int squashfs_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (ffffffff8146ffd0)
Location: fs/squashfs/xattr.c:105
Inline: False
Direct callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
**Symbols:**

```
ffffffff8146ffd0-ffffffff8147025e: squashfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int squashfs_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (ffffffff814c6a40)
Location: fs/squashfs/xattr.c:105
Inline: False
Direct callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
**Symbols:**

```
ffffffff814c6a40-ffffffff814c6cce: squashfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int squashfs_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (ffffffff81551d30)
Location: fs/squashfs/xattr.c:105
Inline: False
Direct callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
**Symbols:**

```
ffffffff81551d30-ffffffff81551ffe: squashfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int squashfs_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (ffffffff815f31f0)
Location: fs/squashfs/xattr.c:105
Inline: False
Direct callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
**Symbols:**

```
ffffffff815f31f0-ffffffff815f34be: squashfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int squashfs_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (ffffffff8162b2e0)
Location: fs/squashfs/xattr.c:105
Inline: False
Direct callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
**Symbols:**

```
ffffffff8162b2e0-ffffffff8162b5ae: squashfs_xattr_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int squashfs_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (ffffffff816646b0)
Location: fs/squashfs/xattr.c:105
Inline: False
Direct callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
**Symbols:**

```
ffffffff816646b0-ffffffff8166497e: squashfs_xattr_get (STB_LOCAL)
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
In fs/squashfs/xattr.c (ffff8000104deb38)
Location: fs/squashfs/xattr.c:105
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (c06a0574)
Location: fs/squashfs/xattr.c:105
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int squashfs_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/xattr.c (c00000000061aa60)
Location: fs/squashfs/xattr.c:105
Inline: False
Direct callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
```
**Symbols:**

```
c00000000061aa60-c00000000061adc8: squashfs_xattr_get (STB_LOCAL)
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
In fs/squashfs/xattr.c (ffffffe000353318)
Location: fs/squashfs/xattr.c:105
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff813f8fc1)
Location: fs/squashfs/xattr.c:105
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff813e9a41)
Location: fs/squashfs/xattr.c:105
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff813f6341)
Location: fs/squashfs/xattr.c:105
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
In fs/squashfs/xattr.c (ffffffff8140bfd1)
Location: fs/squashfs/xattr.c:105
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:squashfs_xattr_handler_get
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
