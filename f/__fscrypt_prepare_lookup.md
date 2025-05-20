# Function: <code>__fscrypt_prepare_lookup</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff812d0b70)
Location: fs/crypto/hooks.c:96
Inline: True
```
**Symbols:**

```
ffffffff812d0b70-ffffffff812d0bd0: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff812fb3a0)
Location: fs/crypto/hooks.c:97
Inline: True
```
**Symbols:**

```
ffffffff812fb3a0-ffffffff812fb400: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813107b0)
Location: fs/crypto/hooks.c:97
Inline: True
```
**Symbols:**

```
ffffffff813107b0-ffffffff81310810: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81337da0)
Location: fs/crypto/hooks.c:107
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff81337da0-ffffffff81337e1d: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8134be20)
Location: fs/crypto/hooks.c:107
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff8134be20-ffffffff8134be9d: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81391640)
Location: fs/crypto/hooks.c:109
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff81391640-ffffffff813916bd: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a2ce0)
Location: fs/crypto/hooks.c:99
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff813a2ce0-ffffffff813a2d4e: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a9f20)
Location: fs/crypto/hooks.c:99
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff813a9f20-ffffffff813a9f8e: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813f97b0)
Location: fs/crypto/hooks.c:99
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff81cc641a-ffffffff81cc642e: __fscrypt_prepare_lookup.cold (STB_LOCAL)
ffffffff813f9760-ffffffff813f97da: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8146c666)
Location: fs/crypto/hooks.c:99
Inline: True
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff81e78882-ffffffff81e7889c: __fscrypt_prepare_lookup.cold (STB_LOCAL)
ffffffff8146c610-ffffffff8146c69e: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (ffffffff814fda26)
Location: fs/crypto/hooks.c:97
Inline: True
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff8206a5d5-ffffffff8206a5ef: __fscrypt_prepare_lookup.cold (STB_LOCAL)
ffffffff814fd9d0-ffffffff814fda5e: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:97
Inline: True
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff820ea3c6-ffffffff820ea3e0: __fscrypt_prepare_lookup.cold (STB_LOCAL)
ffffffff81534fb0-ffffffff8153503e: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:97
Inline: True
Direct callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff821c6e7b-ffffffff821c6e95: __fscrypt_prepare_lookup.cold (STB_LOCAL)
ffffffff81569f70-ffffffff81569ffe: __fscrypt_prepare_lookup (STB_GLOBAL)
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
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffff80001040cb08)
Location: fs/crypto/hooks.c:107
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffff80001040cb08-ffff80001040cbf4: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c05d97a0)
Location: fs/crypto/hooks.c:107
Inline: True
```
**Symbols:**

```
c05d97a0-c05d9834: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c0000000005199e0)
Location: fs/crypto/hooks.c:107
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
c0000000005199e0-c000000000519afc: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffe0002b609c)
Location: fs/crypto/hooks.c:107
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffe0002b609c-ffffffe0002b6166: __fscrypt_prepare_lookup (STB_GLOBAL)
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
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81344400)
Location: fs/crypto/hooks.c:107
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff81344400-ffffffff8134447d: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813350e0)
Location: fs/crypto/hooks.c:107
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff813350e0-ffffffff8133515d: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81341ed0)
Location: fs/crypto/hooks.c:107
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff81341ed0-ffffffff81341f4d: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_lookup(struct inode *dir, struct dentry *dentry, struct fscrypt_name *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813551d0)
Location: fs/crypto/hooks.c:107
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_fname_prepare_lookup
```
**Symbols:**

```
ffffffff813551d0-ffffffff8135524f: __fscrypt_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fscrypt_name *fname</code>
</li>
</ul>
</details>
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
