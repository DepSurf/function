# Function: <code>ext4_xattr_block_get</code>

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
In fs/ext4/xattr.c (ffffffff812de1f6)
Location: fs/ext4/xattr.c:274
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff8130de24)
Location: fs/ext4/xattr.c:294
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff81323ba4)
Location: fs/ext4/xattr.c:299
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff8133d090)
Location: fs/ext4/xattr.c:481
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff81361670)
Location: fs/ext4/xattr.c:491
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff8138fe40)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff813a8a8e)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff813d2c9d)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff813ec37d)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_block_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81437970)
Location: fs/ext4/xattr.c:514
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff81437970-ffffffff81437bcf: ext4_xattr_block_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_block_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814504a0)
Location: fs/ext4/xattr.c:514
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff814504a0-ffffffff814506ff: ext4_xattr_block_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_block_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81455d70)
Location: fs/ext4/xattr.c:514
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff81455d70-ffffffff81455fcf: ext4_xattr_block_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_block_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814aa7c0)
Location: fs/ext4/xattr.c:514
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff814aa7c0-ffffffff814aaa1f: ext4_xattr_block_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_block_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815312c0)
Location: fs/ext4/xattr.c:529
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff815312c0-ffffffff81531523: ext4_xattr_block_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_block_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815cfa50)
Location: fs/ext4/xattr.c:545
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff815cfa50-ffffffff815cfc15: ext4_xattr_block_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_block_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81607490)
Location: fs/ext4/xattr.c:574
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff81607490-ffffffff81607665: ext4_xattr_block_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_block_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff816401d0)
Location: fs/ext4/xattr.c:574
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_get
```
**Symbols:**

```
ffffffff816401d0-ffffffff816403a5: ext4_xattr_block_get (STB_LOCAL)
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
In fs/ext4/xattr.c (ffff8000104c5294)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (c0689344)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (c0000000005fcf94)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffe00033fb1a)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff813e495d)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff813d53dd)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff813e1cdd)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
In fs/ext4/xattr.c (ffffffff813f70ed)
Location: fs/ext4/xattr.c:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_get
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
