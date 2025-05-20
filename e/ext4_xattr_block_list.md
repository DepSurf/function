# Function: <code>ext4_xattr_block_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812ddddf)
Location: fs/ext4/xattr.c:423
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130d9d4)
Location: fs/ext4/xattr.c:448
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff81323754)
Location: fs/ext4/xattr.c:453
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff8133d2b5)
Location: fs/ext4/xattr.c:648
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff81361895)
Location: fs/ext4/xattr.c:658
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff81390095)
Location: fs/ext4/xattr.c:690
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff813a8ce1)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff813d2f25)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff813ec605)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_block_list(struct dentry *dentry, char *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81437bd0)
Location: fs/ext4/xattr.c:691
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_listxattr
```
**Symbols:**

```
ffffffff81437bd0-ffffffff81437d53: ext4_xattr_block_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_block_list(struct dentry *dentry, char *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81450700)
Location: fs/ext4/xattr.c:691
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_listxattr
```
**Symbols:**

```
ffffffff81450700-ffffffff81450883: ext4_xattr_block_list (STB_LOCAL)
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
In fs/ext4/xattr.c (ffffffff81457963)
Location: fs/ext4/xattr.c:691
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff814aba43)
Location: fs/ext4/xattr.c:691
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff815338eb)
Location: fs/ext4/xattr.c:706
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff815d1ecb)
Location: fs/ext4/xattr.c:722
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff8160996b)
Location: fs/ext4/xattr.c:750
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff816426bb)
Location: fs/ext4/xattr.c:750
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffff8000104c5500)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (c0689588)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (c0000000005fd298)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffe00033fcf4)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff813e4be5)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff813d5665)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff813e1f65)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
In fs/ext4/xattr.c (ffffffff813f7375)
Location: fs/ext4/xattr.c:689
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_listxattr
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
</ul>
