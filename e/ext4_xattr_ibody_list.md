# Function: <code>ext4_xattr_ibody_list</code>

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
In fs/ext4/xattr.c (ffffffff812dddc4)
Location: fs/ext4/xattr.c:460
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
In fs/ext4/xattr.c (ffffffff8130d9b7)
Location: fs/ext4/xattr.c:485
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
In fs/ext4/xattr.c (ffffffff81323737)
Location: fs/ext4/xattr.c:490
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
In fs/ext4/xattr.c (ffffffff8133d26b)
Location: fs/ext4/xattr.c:684
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
In fs/ext4/xattr.c (ffffffff8136184b)
Location: fs/ext4/xattr.c:694
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
In fs/ext4/xattr.c (ffffffff81390071)
Location: fs/ext4/xattr.c:723
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
In fs/ext4/xattr.c (ffffffff813a8cc1)
Location: fs/ext4/xattr.c:719
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
In fs/ext4/xattr.c (ffffffff813d2f00)
Location: fs/ext4/xattr.c:719
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
In fs/ext4/xattr.c (ffffffff813ec5e0)
Location: fs/ext4/xattr.c:719
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
int ext4_xattr_ibody_list(struct dentry *dentry, char *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81436470)
Location: fs/ext4/xattr.c:721
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_listxattr
```
**Symbols:**

```
ffffffff81436470-ffffffff81436571: ext4_xattr_ibody_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_ibody_list(struct dentry *dentry, char *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144ee90)
Location: fs/ext4/xattr.c:721
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_listxattr
```
**Symbols:**

```
ffffffff8144ee90-ffffffff8144ef91: ext4_xattr_ibody_list (STB_LOCAL)
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
In fs/ext4/xattr.c (ffffffff8145793e)
Location: fs/ext4/xattr.c:721
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
In fs/ext4/xattr.c (ffffffff814aba1e)
Location: fs/ext4/xattr.c:721
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
In fs/ext4/xattr.c (ffffffff815338ae)
Location: fs/ext4/xattr.c:736
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
In fs/ext4/xattr.c (ffffffff815d1e8e)
Location: fs/ext4/xattr.c:752
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
In fs/ext4/xattr.c (ffffffff8160992e)
Location: fs/ext4/xattr.c:780
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
In fs/ext4/xattr.c (ffffffff8164267e)
Location: fs/ext4/xattr.c:780
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
In fs/ext4/xattr.c (ffff8000104c54e0)
Location: fs/ext4/xattr.c:719
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
In fs/ext4/xattr.c (c0689564)
Location: fs/ext4/xattr.c:719
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
In fs/ext4/xattr.c (c0000000005fd278)
Location: fs/ext4/xattr.c:719
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
In fs/ext4/xattr.c (ffffffe00033fcdc)
Location: fs/ext4/xattr.c:719
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
In fs/ext4/xattr.c (ffffffff813e4bc0)
Location: fs/ext4/xattr.c:719
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
In fs/ext4/xattr.c (ffffffff813d5640)
Location: fs/ext4/xattr.c:719
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
In fs/ext4/xattr.c (ffffffff813e1f40)
Location: fs/ext4/xattr.c:719
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
In fs/ext4/xattr.c (ffffffff813f7350)
Location: fs/ext4/xattr.c:719
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
