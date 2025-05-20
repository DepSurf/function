# Function: <code>fname_encrypt</code>

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
int fname_encrypt(struct inode *inode, const struct qstr *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81289190)
Location: fs/crypto/fname.c:44
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff81289190-ffffffff8128947d: fname_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8129df20)
Location: fs/crypto/fname.c:39
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff8129df20-ffffffff8129e13b: fname_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812ac940)
Location: fs/crypto/fname.c:39
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff812ac940-ffffffff812acba3: fname_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812d0130)
Location: fs/crypto/fname.c:25
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
**Symbols:**

```
ffffffff812d0130-ffffffff812d037a: fname_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812fad90)
Location: fs/crypto/fname.c:38
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff812fad90-ffffffff812faf4c: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:38
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81310686-ffffffff813106b0: fname_encrypt.cold.8 (STB_LOCAL)
ffffffff81310140-ffffffff8131030f: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81337ac2-ffffffff81337afe: fname_encrypt.cold (STB_LOCAL)
ffffffff813375b0-ffffffff81337732: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff8134b66d-ffffffff8134b68b: fname_encrypt.cold (STB_LOCAL)
ffffffff8134b170-ffffffff8134b2fa: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffff80001040bb68)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffff80001040bb68-ffff80001040bd18: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c05d8ca4)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
c05d8ca4-c05d8e68: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c000000000518860)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
c000000000518860-c000000000518a7c: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffe0002b5624)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffe0002b5624-ffffffe0002b5790: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81343c4d-ffffffff81343c6b: fname_encrypt.cold (STB_LOCAL)
ffffffff81343750-ffffffff813438da: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff8133492d-ffffffff8133494b: fname_encrypt.cold (STB_LOCAL)
ffffffff81334430-ffffffff813345ba: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff8134171d-ffffffff8134173b: fname_encrypt.cold (STB_LOCAL)
ffffffff81341220-ffffffff813413aa: fname_encrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fname_encrypt(struct inode *inode, const struct qstr *iname, u8 *out, unsigned int olen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:37
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
  - fs/crypto/hooks.c:__fscrypt_encrypt_symlink
```
**Symbols:**

```
ffffffff81354a1d-ffffffff81354a3b: fname_encrypt.cold (STB_LOCAL)
ffffffff81354520-ffffffff813546aa: fname_encrypt (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *out</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int olen</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fscrypt_str *oname</code>
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
