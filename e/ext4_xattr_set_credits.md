# Function: <code>ext4_xattr_set_credits</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133e143)
Location: fs/ext4/xattr.c:2392
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff8133d870-ffffffff8133d8fc: ext4_xattr_set_credits.part.35 (STB_LOCAL)
ffffffff8133e0a0-ffffffff8133e0d1: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81362723)
Location: fs/ext4/xattr.c:2428
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff81361e50-ffffffff81361edc: ext4_xattr_set_credits.part.35 (STB_LOCAL)
ffffffff81362680-ffffffff813626b1: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81390f3a)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff813906c0-ffffffff8139074f: ext4_xattr_set_credits.part.34 (STB_LOCAL)
ffffffff81390e10-ffffffff81390e41: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a9b3a)
Location: fs/ext4/xattr.c:2443
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff813a92a0-ffffffff813a932f: ext4_xattr_set_credits.part.33 (STB_LOCAL)
ffffffff813a9a10-ffffffff813a9a41: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d40bb)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff813d3510-ffffffff813d359d: ext4_xattr_set_credits.part.0 (STB_LOCAL)
ffffffff813d3f90-ffffffff813d3fc1: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ed79b)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff813ecbf0-ffffffff813ecc7d: ext4_xattr_set_credits.part.0 (STB_LOCAL)
ffffffff813ed670-ffffffff813ed6a1: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8143a620)
Location: fs/ext4/xattr.c:2431
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff8143a620-ffffffff8143a6d2: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81453190)
Location: fs/ext4/xattr.c:2437
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff81453190-ffffffff81453242: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814589f0)
Location: fs/ext4/xattr.c:2437
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff814589f0-ffffffff81458aa2: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814acb00)
Location: fs/ext4/xattr.c:2420
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff814acb00-ffffffff814acbb2: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81534ad0)
Location: fs/ext4/xattr.c:2435
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff81534ad0-ffffffff81534b87: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815d3000)
Location: fs/ext4/xattr.c:2455
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815d3000-ffffffff815d30b7: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8160ab70)
Location: fs/ext4/xattr.c:2498
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff8160ab70-ffffffff8160ac25: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81643930)
Location: fs/ext4/xattr.c:2498
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff81643930-ffffffff816439e5: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c6438)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffff8000104c5ae0-ffff8000104c5b9c: ext4_xattr_set_credits.part.0 (STB_LOCAL)
ffff8000104c62c0-ffff8000104c6334: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (c068a3e0)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
c0689b74-c0689c00: ext4_xattr_set_credits.part.0 (STB_LOCAL)
c068a2dc-c068a31c: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fea0c)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
c0000000005fda80-c0000000005fdb9c: ext4_xattr_set_credits.part.0 (STB_LOCAL)
c0000000005fe880-c0000000005fe8b8: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffe0003408c6)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffe00034019e-ffffffe000340230: ext4_xattr_set_credits.part.0 (STB_LOCAL)
ffffffe00034081a-ffffffe00034086e: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e5d7b)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff813e51d0-ffffffff813e525d: ext4_xattr_set_credits.part.0 (STB_LOCAL)
ffffffff813e5c50-ffffffff813e5c81: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d67fb)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff813d5c50-ffffffff813d5cdd: ext4_xattr_set_credits.part.0 (STB_LOCAL)
ffffffff813d66d0-ffffffff813d6701: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e30fb)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff813e2550-ffffffff813e25dd: ext4_xattr_set_credits.part.0 (STB_LOCAL)
ffffffff813e2fd0-ffffffff813e3001: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_xattr_set_credits(struct inode *inode, size_t value_len, bool is_create, int *credits);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f850b)
Location: fs/ext4/xattr.c:2444
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set
Direct callers:
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/xattr.c:ext4_xattr_set
  - fs/ext4/acl.c:ext4_set_acl
```
**Symbols:**

```
ffffffff813f7960-ffffffff813f79ed: ext4_xattr_set_credits.part.0 (STB_LOCAL)
ffffffff813f83e0-ffffffff813f8411: ext4_xattr_set_credits (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
