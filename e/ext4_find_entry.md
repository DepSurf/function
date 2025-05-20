# Function: <code>ext4_find_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a3d20)
Location: fs/ext4/namei.c:1344
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff812a3d20-ffffffff812a4424: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d2c90)
Location: fs/ext4/namei.c:1353
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff812d2c90-ffffffff812d338d: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e89e0)
Location: fs/ext4/namei.c:1355
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff812e89e0-ffffffff812e90dd: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81318380)
Location: fs/ext4/namei.c:1337
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff81318380-ffffffff81318868: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133cbe0)
Location: fs/ext4/namei.c:1338
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff8133cbe0-ffffffff8133d0b5: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136b130)
Location: fs/ext4/namei.c:1339
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff8136b130-ffffffff8136b663: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813835f0)
Location: fs/ext4/namei.c:1340
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff813835f0-ffffffff81383b23: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ad240)
Location: fs/ext4/namei.c:1581
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff813ad240-ffffffff813ad2ee: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c6180)
Location: fs/ext4/namei.c:1582
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff813c6180-ffffffff813c622e: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81412610)
Location: fs/ext4/namei.c:1588
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff81412610-ffffffff814126be: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81425ab0)
Location: fs/ext4/namei.c:1577
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff81425ab0-ffffffff81425b5e: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142c6c0)
Location: fs/ext4/namei.c:1664
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff8142c6c0-ffffffff8142c76e: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814805c0)
Location: fs/ext4/namei.c:1665
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_resetent
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff814805c0-ffffffff8148066e: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815063da)
Location: fs/ext4/namei.c:1711
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_get_parent
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_resetent
```
**Symbols:**

```
ffffffff815034f0-ffffffff81503599: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815a0e8a)
Location: fs/ext4/namei.c:1716
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_get_parent
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_resetent
```
**Symbols:**

```
ffffffff8159e030-ffffffff8159e0d9: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d780a)
Location: fs/ext4/namei.c:1731
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_get_parent
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_resetent
```
**Symbols:**

```
ffffffff815d4940-ffffffff815d49e9: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160fe7a)
Location: fs/ext4/namei.c:1735
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_get_parent
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_resetent
```
**Symbols:**

```
ffffffff8160cff0-ffffffff8160d099: ext4_find_entry (STB_LOCAL)
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
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049dc78)
Location: fs/ext4/namei.c:1582
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffff80001049dc78-ffff80001049dd44: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065f908)
Location: fs/ext4/namei.c:1582
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
c065f908-c065fa18: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c9500)
Location: fs/ext4/namei.c:1582
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
c0000000005c9500-c0000000005c9604: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000320860)
Location: fs/ext4/namei.c:1582
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffe000320860-ffffffe0003208ee: ext4_find_entry (STB_LOCAL)
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
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813be760)
Location: fs/ext4/namei.c:1582
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff813be760-ffffffff813be80e: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813af1f0)
Location: fs/ext4/namei.c:1582
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff813af1f0-ffffffff813af29e: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bbd60)
Location: fs/ext4/namei.c:1582
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff813bbd60-ffffffff813bbded: ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_find_entry(struct inode *dir, const struct qstr *d_name, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d0cf0)
Location: fs/ext4/namei.c:1582
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_cross_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_get_parent
```
**Symbols:**

```
ffffffff813d0cf0-ffffffff813d0d9e: ext4_find_entry (STB_LOCAL)
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
