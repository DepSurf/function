# Function: <code>ext4_xattr_inode_inc_ref_all</code>

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
In fs/ext4/xattr.c (ffffffff8133cb35)
Location: fs/ext4/xattr.c:1060
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813610e9)
Location: fs/ext4/xattr.c:1075
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff8138f355)
Location: fs/ext4/xattr.c:1103
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813a7da2)
Location: fs/ext4/xattr.c:1095
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813d2160)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813eb840)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_inode_inc_ref_all(handle_t *handle, struct inode *parent, struct ext4_xattr_entry *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81436c10)
Location: fs/ext4/xattr.c:1049
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81436c10-ffffffff81436d9d: ext4_xattr_inode_inc_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_inode_inc_ref_all(handle_t *handle, struct inode *parent, struct ext4_xattr_entry *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144f640)
Location: fs/ext4/xattr.c:1052
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8144f640-ffffffff8144f7cd: ext4_xattr_inode_inc_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_inode_inc_ref_all(handle_t *handle, struct inode *parent, struct ext4_xattr_entry *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81454d20)
Location: fs/ext4/xattr.c:1052
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81454d20-ffffffff81454ead: ext4_xattr_inode_inc_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_inode_inc_ref_all(handle_t *handle, struct inode *parent, struct ext4_xattr_entry *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a8e40)
Location: fs/ext4/xattr.c:1053
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff814a8e40-ffffffff814a8fcd: ext4_xattr_inode_inc_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_inode_inc_ref_all(handle_t *handle, struct inode *parent, struct ext4_xattr_entry *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815304e0)
Location: fs/ext4/xattr.c:1052
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff815304e0-ffffffff81530688: ext4_xattr_inode_inc_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_inode_inc_ref_all(handle_t *handle, struct inode *parent, struct ext4_xattr_entry *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815ce5b0)
Location: fs/ext4/xattr.c:1068
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff815ce5b0-ffffffff815ce758: ext4_xattr_inode_inc_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_inode_inc_ref_all(handle_t *handle, struct inode *parent, struct ext4_xattr_entry *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81605e80)
Location: fs/ext4/xattr.c:1096
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81605e80-ffffffff81606028: ext4_xattr_inode_inc_ref_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_inode_inc_ref_all(handle_t *handle, struct inode *parent, struct ext4_xattr_entry *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8163eba0)
Location: fs/ext4/xattr.c:1096
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8163eba0-ffffffff8163ed48: ext4_xattr_inode_inc_ref_all (STB_LOCAL)
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
In fs/ext4/xattr.c (ffff8000104c47cc)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (c0688780)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (c0000000005fc0d8)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffe00033f0ee)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813e3e20)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813d48a0)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813e11a0)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813f65bb)
Location: fs/ext4/xattr.c:1096
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
