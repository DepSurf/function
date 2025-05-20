# Function: <code>fscrypt_fname_encrypted_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u32 fscrypt_fname_encrypted_size(struct inode *inode, u32 ilen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8128907a)
Location: fs/crypto/fname.c:227
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_alloc_buffer
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81289020-ffffffff81289070: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 fscrypt_fname_encrypted_size(const struct inode *inode, u32 ilen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8129de1a)
Location: fs/crypto/fname.c:212
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_alloc_buffer
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff8129ddc0-ffffffff8129de02: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 fscrypt_fname_encrypted_size(const struct inode *inode, u32 ilen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812ac8bf)
Location: fs/crypto/fname.c:214
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_alloc_buffer
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff812ac870-ffffffff812ac8b0: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 fscrypt_fname_encrypted_size(const struct inode *inode, u32 ilen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812d00cf)
Location: fs/crypto/fname.c:191
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_fname_alloc_buffer
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff812d0080-ffffffff812d00c0: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812faffe)
Location: fs/crypto/fname.c:184
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff812fb250-ffffffff812fb29c: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813103be)
Location: fs/crypto/fname.c:186
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff81310610-ffffffff8131065c: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8133790c)
Location: fs/crypto/fname.c:185
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff81337a40-ffffffff81337a8c: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8134b300)
Location: fs/crypto/fname.c:181
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff8134b300-ffffffff8134b354: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81390cd0)
Location: fs/crypto/fname.c:262
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff81390cd0-ffffffff81390d34: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fscrypt_fname_encrypted_size(const union fscrypt_policy *policy, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a2190)
Location: fs/crypto/fname.c:236
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_prepare_symlink
```
**Symbols:**

```
ffffffff813a2190-ffffffff813a21ea: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fscrypt_fname_encrypted_size(const union fscrypt_policy *policy, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a9310)
Location: fs/crypto/fname.c:236
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:fscrypt_prepare_symlink
```
**Symbols:**

```
ffffffff813a9310-ffffffff813a9361: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const union fscrypt_policy *policy, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813f8b9f)
Location: fs/crypto/fname.c:260
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
Direct callers:
  - fs/crypto/hooks.c:fscrypt_prepare_symlink
```
**Symbols:**

```
ffffffff813f8e30-ffffffff813f8e81: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const union fscrypt_policy *policy, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8146b93d)
Location: fs/crypto/fname.c:267
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
Direct callers:
  - fs/crypto/hooks.c:fscrypt_prepare_symlink
```
**Symbols:**

```
ffffffff8146bbe0-ffffffff8146bc40: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff814fcc1d)
Location: fs/crypto/fname.c:299
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff814fc610-ffffffff814fc677: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8153419d)
Location: fs/crypto/fname.c:299
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff81533b80-ffffffff81533be8: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8156912d)
Location: fs/crypto/fname.c:299
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff81568b10-ffffffff81568b78: fscrypt_fname_encrypted_size (STB_GLOBAL)
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
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffff80001040bd18)
Location: fs/crypto/fname.c:181
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffff80001040bd18-ffff80001040bdb0: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c05d8e68)
Location: fs/crypto/fname.c:181
Inline: False
```
**Symbols:**

```
c05d8e68-c05d8ee0: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c000000000518a80)
Location: fs/crypto/fname.c:181
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
c000000000518a80-c000000000518b1c: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffe0002b5790)
Location: fs/crypto/fname.c:181
Inline: True
```
**Symbols:**

```
ffffffe0002b5790-ffffffe0002b581a: fscrypt_fname_encrypted_size (STB_GLOBAL)
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
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813438e0)
Location: fs/crypto/fname.c:181
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff813438e0-ffffffff81343934: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813345c0)
Location: fs/crypto/fname.c:181
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff813345c0-ffffffff81334614: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813413b0)
Location: fs/crypto/fname.c:181
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff813413b0-ffffffff81341404: fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool fscrypt_fname_encrypted_size(const struct inode *inode, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813546b0)
Location: fs/crypto/fname.c:181
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff813546b0-ffffffff81354704: fscrypt_fname_encrypted_size (STB_GLOBAL)
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
<code>u32 orig_len</code>
</li>
<li>
<b>Param added. </b>
<code>u32 max_len</code>
</li>
<li>
<b>Param added. </b>
<code>u32 *encrypted_len_ret</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 ilen</code>
</li>
<li>
<b>Return type changed. </b>
<code>u32</code> ➡️ <code>bool</code>
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
<b>Param added. </b>
<code>const union fscrypt_policy *policy</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct inode *inode</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>const union fscrypt_policy *policy</code>
</li>
</ul>
</details>
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
