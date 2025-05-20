# Function: <code>ext4_expand_inode_array</code>

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
In fs/ext4/xattr.c (ffffffff8133a6ea)
Location: fs/ext4/xattr.c:2750
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffff8135eac0)
Location: fs/ext4/xattr.c:2786
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffff8138d433)
Location: fs/ext4/xattr.c:2803
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffff813a6043)
Location: fs/ext4/xattr.c:2808
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffff813d036f)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffff813e9a3f)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array **ea_inode_array, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81435d70)
Location: fs/ext4/xattr.c:2796
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff81435d70-ffffffff81435e47: ext4_expand_inode_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array **ea_inode_array, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144e7b0)
Location: fs/ext4/xattr.c:2803
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff8144e7b0-ffffffff8144e887: ext4_expand_inode_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array **ea_inode_array, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814542c0)
Location: fs/ext4/xattr.c:2803
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff814542c0-ffffffff81454397: ext4_expand_inode_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array **ea_inode_array, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a8380)
Location: fs/ext4/xattr.c:2786
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff814a8380-ffffffff814a8457: ext4_expand_inode_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array **ea_inode_array, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8152fe80)
Location: fs/ext4/xattr.c:2801
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff8152fe80-ffffffff8152ff5c: ext4_expand_inode_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array **ea_inode_array, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815ce1a0)
Location: fs/ext4/xattr.c:2827
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff815ce1a0-ffffffff815ce27c: ext4_expand_inode_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array **ea_inode_array, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81605a50)
Location: fs/ext4/xattr.c:2874
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff81605a50-ffffffff81605b42: ext4_expand_inode_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_expand_inode_array(struct ext4_xattr_inode_array **ea_inode_array, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8163e730)
Location: fs/ext4/xattr.c:2874
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
```
**Symbols:**

```
ffffffff8163e730-ffffffff8163e859: ext4_expand_inode_array (STB_LOCAL)
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
In fs/ext4/xattr.c (ffff8000104c3dd8)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (c0686a48)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (c0000000005f9bdc)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffe00033db0c)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffff813e201f)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffff813d2a9f)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffff813df39f)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
In fs/ext4/xattr.c (ffffffff813f47bf)
Location: fs/ext4/xattr.c:2809
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_dec_ref_all
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
