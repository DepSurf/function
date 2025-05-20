# Function: <code>crypto_alloc_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8139cc30)
Location: crypto/api.c:424
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_calculate_md5
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - crypto/crypto_null.c:crypto_get_default_null_skcipher
  - net/ipv4/tcp.c:tcp_alloc_md5sig_pool
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
**Symbols:**

```
ffffffff8139cc30-ffffffff8139ccfc: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813d9af0)
Location: crypto/api.c:424
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_init_sym_kernel
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
**Symbols:**

```
ffffffff813d9af0-ffffffff813d9bca: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813f1450)
Location: crypto/api.c:408
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
**Symbols:**

```
ffffffff813f1450-ffffffff813f1525: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813fd6d0)
Location: crypto/api.c:408
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
**Symbols:**

```
ffffffff813fd6d0-ffffffff813fd7a2: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81425c60)
Location: crypto/api.c:409
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
**Symbols:**

```
ffffffff81425c60-ffffffff81425d2d: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81458980)
Location: crypto/api.c:418
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/pstore/platform.c:pstore_register
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
**Symbols:**

```
ffffffff81458980-ffffffff81458a50: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81476060)
Location: crypto/api.c:418
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
**Symbols:**

```
ffffffff81476060-ffffffff81476130: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a3cb0)
Location: crypto/api.c:413
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814a3cb0-ffffffff814a3d8b: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814be8e0)
Location: crypto/api.c:414
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814be8e0-ffffffff814be9bb: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8151f000)
Location: crypto/api.c:402
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/pstore/platform.c:allocate_buf_for_compression
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff8151f000-ffffffff8151f09f: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8153be60)
Location: crypto/api.c:402
Inline: False
Direct callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
  - crypto/xts.c:xts_init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff8153be60-ffffffff8153beff: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81544550)
Location: crypto/api.c:402
Inline: False
Direct callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
  - crypto/xts.c:xts_init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff81544550-ffffffff815445ef: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff815a4cf0)
Location: crypto/api.c:402
Inline: False
Direct callers:
  - fs/pstore/platform.c:allocate_buf_for_compression
  - crypto/xts.c:xts_init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff815a4cf0-ffffffff815a4d8f: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8164ba30)
Location: crypto/api.c:457
Inline: False
Direct callers:
  - crypto/xts.c:xts_init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff8164ba30-ffffffff8164bad2: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81704b00)
Location: crypto/api.c:456
Inline: False
Direct callers:
  - crypto/xts.c:xts_init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff81704b00-ffffffff81704ba2: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8173ee40)
Location: crypto/api.c:450
Inline: False
Direct callers:
  - crypto/xts.c:xts_init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff8173ee40-ffffffff8173eee9: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8177fc20)
Location: crypto/api.c:450
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff8177fc20-ffffffff8177fcc9: crypto_alloc_base (STB_GLOBAL)
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
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffff8000105b7950)
Location: crypto/api.c:414
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffff8000105b7950-ffff8000105b7a28: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (c076684c)
Location: crypto/api.c:414
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
c076684c-c0766920: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (c00000000073ca70)
Location: crypto/api.c:414
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
c00000000073ca70-c00000000073cbd0: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffe0003fe254)
Location: crypto/api.c:414
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffe0003fe254-ffffffe0003fe2ee: crypto_alloc_base (STB_GLOBAL)
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
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b6ec0)
Location: crypto/api.c:414
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814b6ec0-ffffffff814b6f9b: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a78e0)
Location: crypto/api.c:414
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814a78e0-ffffffff814a79bb: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b2f50)
Location: crypto/api.c:414
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814b2f50-ffffffff814b302b: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct crypto_tfm *crypto_alloc_base(const char *alg_name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814cb9d0)
Location: crypto/api.c:414
Inline: False
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_prepare
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - crypto/xts.c:init_tfm
  - crypto/drbg.c:drbg_init_sym_kernel
```
**Symbols:**

```
ffffffff814cb9d0-ffffffff814cbaab: crypto_alloc_base (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
