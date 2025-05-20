# Function: <code>__fuse_write_file_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_conn *fc, struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81314ed0)
Location: fs/fuse/file.c:1566
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff81314ed0-ffffffff81314f18: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_conn *fc, struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81349550)
Location: fs/fuse/file.c:1579
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff81349550-ffffffff813495a2: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_conn *fc, struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8135ee50)
Location: fs/fuse/file.c:1580
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff8135ee50-ffffffff8135eea2: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_conn *fc, struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81373a20)
Location: fs/fuse/file.c:1575
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff81373a20-ffffffff81373a72: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_conn *fc, struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81398750)
Location: fs/fuse/file.c:1583
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff81398750-ffffffff813987a7: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_conn *fc, struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813c8af0)
Location: fs/fuse/file.c:1584
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff813c8af0-ffffffff813c8b46: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_conn *fc, struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e1bd0)
Location: fs/fuse/file.c:1590
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff813e1bd0-ffffffff813e1c26: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8140da30)
Location: fs/fuse/file.c:1655
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff8140da30-ffffffff8140da8d: __fuse_write_file_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81426c30)
Location: fs/fuse/file.c:1756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff81426c30-ffffffff81426c8d: __fuse_write_file_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8147bf75)
Location: fs/fuse/file.c:1767
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496d9f)
Location: fs/fuse/file.c:1807
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149be9f)
Location: fs/fuse/file.c:1818
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f3b8c)
Location: fs/fuse/file.c:1824
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_inode
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff814eeae0-ffffffff814eeb66: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8158349b)
Location: fs/fuse/file.c:1839
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_inode
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8157e6f0-ffffffff8157e7a5: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8162943b)
Location: fs/fuse/file.c:1874
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_inode
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81623d90-ffffffff81623e45: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8166164b)
Location: fs/fuse/file.c:1851
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_inode
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8165c170-ffffffff8165c225: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fuse_file *__fuse_write_file_get(struct fuse_inode *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169b50b)
Location: fs/fuse/file.c:1871
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_inode
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81695ed0-ffffffff81695f85: __fuse_write_file_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffff80001050b258)
Location: fs/fuse/file.c:1756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffff80001050b258-ffff80001050b2fc: __fuse_write_file_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (c06c6790)
Location: fs/fuse/file.c:1756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
c06c6790-c06c67f8: __fuse_write_file_get.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (c000000000650d60)
Location: fs/fuse/file.c:1756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
c000000000650d60-c000000000650e4c: __fuse_write_file_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffe000375cea)
Location: fs/fuse/file.c:1756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffe000375cea-ffffffe000375d76: __fuse_write_file_get.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8141f210)
Location: fs/fuse/file.c:1756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff8141f210-ffffffff8141f26d: __fuse_write_file_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8140fc90)
Location: fs/fuse/file.c:1756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff8140fc90-ffffffff8140fced: __fuse_write_file_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff8141b3b0)
Location: fs/fuse/file.c:1756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff8141b3b0-ffffffff8141b40d: __fuse_write_file_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (ffffffff81432030)
Location: fs/fuse/file.c:1756
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_write_inode
```
**Symbols:**

```
ffffffff81432030-ffffffff8143208b: __fuse_write_file_get.isra.0 (STB_LOCAL)
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
