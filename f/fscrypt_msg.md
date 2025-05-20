# Function: <code>fscrypt_msg</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void fscrypt_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812fa824)
Location: fs/crypto/crypto.c:426
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - fs/crypto/keyinfo.c:find_and_lock_process_key
```
**Symbols:**

```
ffffffff812fa824-ffffffff812fa8f0: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fscrypt_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8130fba4)
Location: fs/crypto/crypto.c:428
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - fs/crypto/keyinfo.c:find_and_lock_process_key
```
**Symbols:**

```
ffffffff8130fba4-ffffffff8130fc70: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fscrypt_msg(struct super_block *sb, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813370ac)
Location: fs/crypto/crypto.c:456
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyinfo.c:derive_essiv_salt
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - fs/crypto/keyinfo.c:find_and_lock_process_key
```
**Symbols:**

```
ffffffff813370ac-ffffffff81337178: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8134ac74)
Location: fs/crypto/crypto.c:454
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff8134ac74-ffffffff8134ad48: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff813903e4)
Location: fs/crypto/crypto.c:332
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/fname.c:fscrypt_do_sha256
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:check_for_busy_inodes
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
```
**Symbols:**

```
ffffffff813903e4-ffffffff813904b8: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81beac7c)
Location: fs/crypto/crypto.c:332
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:check_for_busy_inodes
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff81beac7c-ffffffff81bead69: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81bdccc9)
Location: fs/crypto/crypto.c:332
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff81bdccc9-ffffffff81bdcdb6: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81cc60b1)
Location: fs/crypto/crypto.c:332
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff81cc60b1-ffffffff81cc619e: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81e782f2)
Location: fs/crypto/crypto.c:340
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff81e782f2-ffffffff81e78412: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff814fbaf0)
Location: fs/crypto/crypto.c:340
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff814fbaf0-ffffffff814fbc2c: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81532e20)
Location: fs/crypto/crypto.c:347
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff81532e20-ffffffff81532f5c: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81567d20)
Location: fs/crypto/crypto.c:365
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/policy.c:fscrypt_supported_v2_policy
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
**Symbols:**

```
ffffffff81567d20-ffffffff81567e5c: fscrypt_msg (STB_GLOBAL)
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
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffff80001040b5d0)
Location: fs/crypto/crypto.c:454
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
**Symbols:**

```
ffff80001040b5d0-ffff80001040b6b0: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c05d87ac)
Location: fs/crypto/crypto.c:454
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
c05d87ac-c05d887c: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (c000000000518154)
Location: fs/crypto/crypto.c:454
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
c000000000518154-c00000000051825c: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffe0002b515c)
Location: fs/crypto/crypto.c:454
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffe0002b515c-ffffffe0002b51fc: fscrypt_msg (STB_GLOBAL)
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
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81343254)
Location: fs/crypto/crypto.c:454
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff81343254-ffffffff81343328: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81333f34)
Location: fs/crypto/crypto.c:454
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff81333f34-ffffffff81334008: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81340d24)
Location: fs/crypto/crypto.c:454
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff81340d24-ffffffff81340df8: fscrypt_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fscrypt_msg(const struct inode *inode, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81354024)
Location: fs/crypto/crypto.c:454
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/hkdf.c:fscrypt_init_hkdf
  - fs/crypto/hooks.c:fscrypt_file_open
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_v2_file_key
  - fs/crypto/keysetup.c:fscrypt_set_derived_key
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:derive_essiv_salt
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup.c:fscrypt_allocate_skcipher
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/crypto/policy.c:fscrypt_supported_policy
  - fs/crypto/policy.c:fscrypt_supported_policy
```
**Symbols:**

```
ffffffff81354024-ffffffff813540f8: fscrypt_msg (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct super_block *sb</code>
</li>
</ul>
</details>
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
