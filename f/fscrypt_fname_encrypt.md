# Function: <code>fscrypt_fname_encrypt</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_fname_encrypt(const struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:112
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81391052-ffffffff81391070: fscrypt_fname_encrypt.cold (STB_LOCAL)
ffffffff81390b40-ffffffff81390cc9: fscrypt_fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fscrypt_fname_encrypt(const struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:86
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81beadc8-ffffffff81beade6: fscrypt_fname_encrypt.cold (STB_LOCAL)
ffffffff813a2000-ffffffff813a2189: fscrypt_fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fscrypt_fname_encrypt(const struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:86
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81bdce15-ffffffff81bdce33: fscrypt_fname_encrypt.cold (STB_LOCAL)
ffffffff813a9180-ffffffff813a9306: fscrypt_fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_fname_encrypt(const struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:90
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81cc6389-ffffffff81cc63a7: fscrypt_fname_encrypt.cold (STB_LOCAL)
ffffffff813f8950-ffffffff813f8ad6: fscrypt_fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_fname_encrypt(const struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:97
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81e7880e-ffffffff81e7882f: fscrypt_fname_encrypt.cold (STB_LOCAL)
ffffffff8146b6a0-ffffffff8146b882: fscrypt_fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_fname_encrypt(const struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff814fc3f0)
Location: fs/crypto/fname.c:98
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff814fc3f0-ffffffff814fc5f6: fscrypt_fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_fname_encrypt(const struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81533960)
Location: fs/crypto/fname.c:98
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81533960-ffffffff81533b66: fscrypt_fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_fname_encrypt(const struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff815688f0)
Location: fs/crypto/fname.c:98
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff815688f0-ffffffff81568af6: fscrypt_fname_encrypt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
