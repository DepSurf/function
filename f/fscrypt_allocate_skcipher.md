# Function: <code>fscrypt_allocate_skcipher</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:70
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8134dfde-ffffffff8134e051: fscrypt_allocate_skcipher.cold (STB_LOCAL)
ffffffff8134d710-ffffffff8134d798: fscrypt_allocate_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:67
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
```
**Symbols:**

```
ffffffff81393eeb-ffffffff81393f5b: fscrypt_allocate_skcipher.cold (STB_LOCAL)
ffffffff81393420-ffffffff813934c3: fscrypt_allocate_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:74
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:setup_per_mode_enc_key
```
**Symbols:**

```
ffffffff813a45c0-ffffffff813a4663: fscrypt_allocate_skcipher (STB_LOCAL)
ffffffff81beaed6-ffffffff81beaf46: fscrypt_allocate_skcipher.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813ab99e)
Location: fs/crypto/keysetup.c:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813fb24d)
Location: fs/crypto/keysetup.c:79
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8146e57a)
Location: fs/crypto/keysetup.c:79
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff814ffbca)
Location: fs/crypto/keysetup.c:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8153719a)
Location: fs/crypto/keysetup.c:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8156c26a)
Location: fs/crypto/keysetup.c:100
Inline: True
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
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffff80001040e8f8)
Location: fs/crypto/keysetup.c:70
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffff80001040e8f8-ffff80001040ea1c: fscrypt_allocate_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c05db404)
Location: fs/crypto/keysetup.c:70
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
c05db404-c05db518: fscrypt_allocate_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c00000000051be20)
Location: fs/crypto/keysetup.c:70
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
c00000000051be20-c00000000051bf9c: fscrypt_allocate_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffe0002b7830)
Location: fs/crypto/keysetup.c:70
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffe0002b7830-ffffffe0002b791c: fscrypt_allocate_skcipher (STB_GLOBAL)
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
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:70
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff813465be-ffffffff81346631: fscrypt_allocate_skcipher.cold (STB_LOCAL)
ffffffff81345cf0-ffffffff81345d78: fscrypt_allocate_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:70
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8133729e-ffffffff81337311: fscrypt_allocate_skcipher.cold (STB_LOCAL)
ffffffff813369d0-ffffffff81336a58: fscrypt_allocate_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:70
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8134408e-ffffffff81344101: fscrypt_allocate_skcipher.cold (STB_LOCAL)
ffffffff813437c0-ffffffff81343848: fscrypt_allocate_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct crypto_skcipher *fscrypt_allocate_skcipher(struct fscrypt_mode *mode, const u8 *raw_key, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:70
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_per_mode_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
```
**Symbols:**

```
ffffffff8135736c-ffffffff813573df: fscrypt_allocate_skcipher.cold (STB_LOCAL)
ffffffff81356aa0-ffffffff81356b28: fscrypt_allocate_skcipher (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
