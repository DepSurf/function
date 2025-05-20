# Function: <code>__fscrypt_prepare_symlink</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff812fb400)
Location: fs/crypto/hooks.c:115
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff812fb400-ffffffff812fb475: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81310810)
Location: fs/crypto/hooks.c:115
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81310810-ffffffff81310885: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81337e20)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81337e20-ffffffff81337e96: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8134bea0)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff8134bea0-ffffffff8134bf16: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813916c0)
Location: fs/crypto/hooks.c:169
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff813916c0-ffffffff81391736: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffff80001040c6a0)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffff80001040c6a0-ffff80001040c738: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c05d9834)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
c05d9834-c05d98b4: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c000000000519b00)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
c000000000519b00-c000000000519bd0: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffe0002b6166)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffe0002b6166-ffffffe0002b61de: __fscrypt_prepare_symlink (STB_GLOBAL)
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
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81344480)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81344480-ffffffff813444f6: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81335160)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81335160-ffffffff813351d6: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81341f50)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81341f50-ffffffff81341fc6: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_symlink(struct inode *dir, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81355250)
Location: fs/crypto/hooks.c:125
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81355250-ffffffff813552c6: __fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
