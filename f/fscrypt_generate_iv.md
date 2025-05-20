# Function: <code>fscrypt_generate_iv</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8130f560)
Location: fs/crypto/crypto.c:136
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
ffffffff8130f560-ffffffff8130f5c2: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81336a80)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
ffffffff81336a80-ffffffff81336ae2: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134a600)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
ffffffff8134a600-ffffffff8134a66c: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8138fda0)
Location: fs/crypto/crypto.c:72
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
```
**Symbols:**

```
ffffffff8138fda0-ffffffff8138fe6a: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a13e0)
Location: fs/crypto/crypto.c:72
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/inline_crypt.c:fscrypt_generate_dun
```
**Symbols:**

```
ffffffff813a13e0-ffffffff813a14ad: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813a8570)
Location: fs/crypto/crypto.c:72
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/inline_crypt.c:fscrypt_generate_dun
```
**Symbols:**

```
ffffffff813a8570-ffffffff813a8640: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813f7cb0)
Location: fs/crypto/crypto.c:72
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/inline_crypt.c:fscrypt_generate_dun
```
**Symbols:**

```
ffffffff813f7cb0-ffffffff813f7d80: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8146a990)
Location: fs/crypto/crypto.c:80
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/inline_crypt.c:fscrypt_generate_dun
```
**Symbols:**

```
ffffffff8146a990-ffffffff8146aa81: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff814fb940)
Location: fs/crypto/crypto.c:80
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/inline_crypt.c:fscrypt_generate_dun
```
**Symbols:**

```
ffffffff814fb940-ffffffff814fba31: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81532c60)
Location: fs/crypto/crypto.c:80
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/inline_crypt.c:fscrypt_generate_dun
```
**Symbols:**

```
ffffffff81532c60-ffffffff81532d51: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 index, const struct fscrypt_inode_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81567b60)
Location: fs/crypto/crypto.c:87
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/inline_crypt.c:fscrypt_generate_dun
```
**Symbols:**

```
ffffffff81567b60-ffffffff81567c51: fscrypt_generate_iv (STB_GLOBAL)
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
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040add0)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
ffff80001040add0-ffff80001040ae5c: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c05d7f54)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
c05d7f54-c05d7ffc: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c000000000517770)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
c000000000517770-c000000000517834: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b4b16)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
ffffffe0002b4b16-ffffffe0002b4b8a: fscrypt_generate_iv (STB_GLOBAL)
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
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81342be0)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
ffffffff81342be0-ffffffff81342c4c: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813338c0)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
ffffffff813338c0-ffffffff8133392c: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813406b0)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
ffffffff813406b0-ffffffff8134071c: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fscrypt_generate_iv(union fscrypt_iv *iv, u64 lblk_num, const struct fscrypt_info *ci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813539b0)
Location: fs/crypto/crypto.c:138
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
```
**Symbols:**

```
ffffffff813539b0-ffffffff81353a1c: fscrypt_generate_iv (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 index</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 lblk_num</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct fscrypt_info *ci</code> ➡️ <code>const struct fscrypt_inode_info *ci</code>
</li>
</ul>
</details>
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
