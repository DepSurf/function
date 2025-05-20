# Function: <code>fscrypt_fname_disk_to_usr</code>

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
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812899e0)
Location: fs/crypto/fname.c:283
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff812899e0-ffffffff81289afb: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8129e6a0)
Location: fs/crypto/fname.c:271
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff8129e6a0-ffffffff8129e7c1: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812ad180)
Location: fs/crypto/fname.c:280
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff812ad180-ffffffff812ad2c2: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812d0930)
Location: fs/crypto/fname.c:257
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
**Symbols:**

```
ffffffff812d0930-ffffffff812d0a72: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812fac50)
Location: fs/crypto/fname.c:252
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff812fac50-ffffffff812fad89: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81310000)
Location: fs/crypto/fname.c:254
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81310000-ffffffff81310139: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81337470)
Location: fs/crypto/fname.c:253
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81337470-ffffffff813375ae: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8134b030)
Location: fs/crypto/fname.c:250
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8134b030-ffffffff8134b16e: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(const struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81390960)
Location: fs/crypto/fname.c:344
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81390960-ffffffff81390b3b: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(const struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a1de0)
Location: fs/crypto/fname.c:315
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813a1de0-ffffffff813a1ff6: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(const struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a8f80)
Location: fs/crypto/fname.c:315
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_ci_compare
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813a8f80-ffffffff813a9180: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_fname_disk_to_usr(const struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:337
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_ci_compare
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81cc6317-ffffffff81cc6389: fscrypt_fname_disk_to_usr.cold (STB_LOCAL)
ffffffff813f8710-ffffffff813f894e: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(const struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8146b440)
Location: fs/crypto/fname.c:344
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_ci_compare
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8146b440-ffffffff8146b69f: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(const struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff814fc900)
Location: fs/crypto/fname.c:369
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_ci_compare
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff814fc900-ffffffff814fcb5f: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fscrypt_fname_disk_to_usr(const struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:369
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_ci_compare
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff820ea321-ffffffff820ea38b: fscrypt_fname_disk_to_usr.cold (STB_LOCAL)
ffffffff81533e70-ffffffff815340db: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_fname_disk_to_usr(const struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:369
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:ext4_ci_compare
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff821c6dd6-ffffffff821c6e40: fscrypt_fname_disk_to_usr.cold (STB_LOCAL)
ffffffff81568e00-ffffffff8156906b: fscrypt_fname_disk_to_usr (STB_GLOBAL)
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
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffff80001040b9e0)
Location: fs/crypto/fname.c:250
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffff80001040b9e0-ffff80001040bb64: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c05d8b2c)
Location: fs/crypto/fname.c:250
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c05d8b2c-c05d8ca4: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c000000000518640)
Location: fs/crypto/fname.c:250
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c000000000518640-c000000000518854: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffe0002b54f6)
Location: fs/crypto/fname.c:250
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffe0002b54f6-ffffffe0002b5624: fscrypt_fname_disk_to_usr (STB_GLOBAL)
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
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81343610)
Location: fs/crypto/fname.c:250
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81343610-ffffffff8134374e: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813342f0)
Location: fs/crypto/fname.c:250
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813342f0-ffffffff8133442e: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813410e0)
Location: fs/crypto/fname.c:250
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813410e0-ffffffff8134121e: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fscrypt_fname_disk_to_usr(struct inode *inode, u32 hash, u32 minor_hash, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813543e0)
Location: fs/crypto/fname.c:250
Inline: False
Direct callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813543e0-ffffffff8135451e: fscrypt_fname_disk_to_usr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct inode *inode</code> ➡️ <code>const struct inode *inode</code>
</li>
</ul>
</details>
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
