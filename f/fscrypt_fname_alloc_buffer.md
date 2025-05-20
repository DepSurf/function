# Function: <code>fscrypt_fname_alloc_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(struct inode *inode, u32 ilen, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81289070)
Location: fs/crypto/fname.c:246
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff81289070-ffffffff8128910b: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 ilen, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8129de10)
Location: fs/crypto/fname.c:230
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff8129de10-ffffffff8129de9d: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 ilen, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812ac8b0)
Location: fs/crypto/fname.c:232
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff812ac8b0-ffffffff812ac91c: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 ilen, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812d00c0)
Location: fs/crypto/fname.c:209
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff812d00c0-ffffffff812d012c: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812fa9d0)
Location: fs/crypto/fname.c:207
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff812fa9d0-ffffffff812faa13: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8130fd50)
Location: fs/crypto/fname.c:209
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8130fd50-ffffffff8130fd93: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81337270)
Location: fs/crypto/fname.c:208
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81337270-ffffffff813372b3: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8134ae30)
Location: fs/crypto/fname.c:205
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8134ae30-ffffffff8134ae73: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81390510)
Location: fs/crypto/fname.c:291
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81390510-ffffffff81390556: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a1a30)
Location: fs/crypto/fname.c:263
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813a1a30-ffffffff813a1a76: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a8bd0)
Location: fs/crypto/fname.c:263
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813a8bd0-ffffffff813a8c14: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813f8340)
Location: fs/crypto/fname.c:287
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813f8340-ffffffff813f8384: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8146af90)
Location: fs/crypto/fname.c:294
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8146af90-ffffffff8146afdc: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff814fc120)
Location: fs/crypto/fname.c:319
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff814fc120-ffffffff814fc16c: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81533690)
Location: fs/crypto/fname.c:319
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81533690-ffffffff815336dc: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81568620)
Location: fs/crypto/fname.c:319
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81568620-ffffffff8156866c: fscrypt_fname_alloc_buffer (STB_GLOBAL)
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
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffff80001040b780)
Location: fs/crypto/fname.c:205
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffff80001040b780-ffff80001040b7d8: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c05d892c)
Location: fs/crypto/fname.c:205
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c05d892c-c05d8974: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c000000000518380)
Location: fs/crypto/fname.c:205
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c000000000518380-c000000000518400: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffe0002b52f4)
Location: fs/crypto/fname.c:205
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffe0002b52f4-ffffffe0002b5352: fscrypt_fname_alloc_buffer (STB_GLOBAL)
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
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81343410)
Location: fs/crypto/fname.c:205
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81343410-ffffffff81343453: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813340f0)
Location: fs/crypto/fname.c:205
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813340f0-ffffffff81334133: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81340ee0)
Location: fs/crypto/fname.c:205
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81340ee0-ffffffff81340f23: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fscrypt_fname_alloc_buffer(const struct inode *inode, u32 max_encrypted_len, struct fscrypt_str *crypto_str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813541e0)
Location: fs/crypto/fname.c:205
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813541e0-ffffffff81354223: fscrypt_fname_alloc_buffer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct inode *inode</code> ➡️ <code>const struct inode *inode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 max_encrypted_len</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 ilen</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct inode *inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, max_encrypted_len, crypto_str</code> ➡️ <code>max_encrypted_len, crypto_str</code>
</li>
</ul>
</details>
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
