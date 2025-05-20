# Function: <code>ext4_get_inline_xattr_pos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812dfb50)
Location: fs/ext4/inline.c:1038
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:empty_inline_dir
```
**Symbols:**

```
ffffffff812dfb50-ffffffff812dfb8b: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8130f7f0)
Location: fs/ext4/inline.c:1038
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8130f7f0-ffffffff8130f832: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81325610)
Location: fs/ext4/inline.c:1056
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81325610-ffffffff81325652: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812f9bd0)
Location: fs/ext4/inline.c:1058
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff812f9bd0-ffffffff812f9c11: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131e210)
Location: fs/ext4/inline.c:1049
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8131e210-ffffffff8131e250: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134c210)
Location: fs/ext4/inline.c:1052
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8134c210-ffffffff8134c250: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81364350)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81364350-ffffffff81364390: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138ce30)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8138ce30-ffffffff8138ce71: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a5880)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff813a5880-ffffffff813a58c1: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f14c0)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff813f14c0-ffffffff813f1501: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81403ba0)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff81403ba0-ffffffff81403be1: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140a240)
Location: fs/ext4/inline.c:1061
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8140a240-ffffffff8140a281: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81460621)
Location: fs/ext4/inline.c:1069
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814deef2)
Location: fs/ext4/inline.c:1065
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81577fc2)
Location: fs/ext4/inline.c:1064
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
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
In fs/ext4/inline.c (ffffffff815af548)
Location: fs/ext4/inline.c:1046
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
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
In fs/ext4/inline.c (ffffffff815e8308)
Location: fs/ext4/inline.c:1045
Inline: True
Inline callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff800010478e28)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffff800010478e28-ffff800010478e88: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063ad4c)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
c063ad4c-c063ada8: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059b380)
Location: fs/ext4/inline.c:1055
Inline: False
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
c00000000059b380-c00000000059b3c8: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000303f92)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffe000303f92-ffffffe000303fe0: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139de60)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8139de60-ffffffff8139dea1: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138e8f0)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8138e8f0-ffffffff8138e931: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139b6c0)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff8139b6c0-ffffffff8139b701: ext4_get_inline_xattr_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *ext4_get_inline_xattr_pos(struct inode *inode, struct ext4_iloc *iloc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813afb80)
Location: fs/ext4/inline.c:1055
Inline: True
Direct callers:
  - fs/ext4/inline.c:empty_inline_dir
  - fs/ext4/inline.c:ext4_delete_inline_entry
  - fs/ext4/inline.c:ext4_find_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
  - fs/ext4/inline.c:ext4_try_add_inline_entry
```
**Symbols:**

```
ffffffff813afb80-ffffffff813afbc1: ext4_get_inline_xattr_pos (STB_LOCAL)
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
