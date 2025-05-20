# Function: <code>crypto_skcipher_decrypt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81288a65)
Location: include/crypto/skcipher.h:425
Inline: True
```
```
In fs/crypto/fname.c (ffffffff812898d1)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
```
```
In fs/ecryptfs/crypto.c (ffffffff81339622)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8133bc96)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8136b884)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8136e8cf)
Location: include/crypto/skcipher.h:425
Inline: True
```
```
In crypto/cts.c (ffffffff813e7a15)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129d692)
Location: include/crypto/skcipher.h:425
Inline: True
```
```
In fs/crypto/fname.c (ffffffff8129e591)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f3c2)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81351a26)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff813820a4)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8138529c)
Location: include/crypto/skcipher.h:425
Inline: True
```
```
In crypto/cts.c (ffffffff81400845)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/xts.c (ffffffff81401c0c)
Location: include/crypto/skcipher.h:425
Inline: True
Inline callers:
  - crypto/xts.c:do_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812ac3f6)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812ad057)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
```
```
In fs/ecryptfs/crypto.c (ffffffff81363e82)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff81366566)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In security/keys/big_key.c (ffffffff8139673d)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81399998)
Location: include/crypto/skcipher.h:459
Inline: True
```
```
In crypto/cts.c (ffffffff8140e0b9)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/xts.c (ffffffff8140efa4)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - crypto/xts.c:do_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812cfc94)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812d0801)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - fs/crypto/fname.c:fname_decrypt
```
```
In fs/ecryptfs/crypto.c (ffffffff81388bf2)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff8138b1e1)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813bf168)
Location: include/crypto/skcipher.h:459
Inline: True
```
```
In crypto/cts.c (ffffffff81436b69)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/xts.c (ffffffff81437a78)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - crypto/xts.c:do_decrypt
```
```
In crypto/gcm.c (ffffffff8143933a)
Location: include/crypto/skcipher.h:459
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_dec_hash_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff812fa523)
Location: include/crypto/skcipher.h:457
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff812fab6e)
Location: include/crypto/skcipher.h:457
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813b7a42)
Location: include/crypto/skcipher.h:457
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813ba0e6)
Location: include/crypto/skcipher.h:457
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813f01fe)
Location: include/crypto/skcipher.h:457
Inline: True
```
```
In crypto/cts.c (ffffffff81469786)
Location: include/crypto/skcipher.h:457
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/xts.c (ffffffff8146a39c)
Location: include/crypto/skcipher.h:457
Inline: True
Inline callers:
  - crypto/xts.c:do_decrypt
```
```
In crypto/gcm.c (ffffffff8146bcc7)
Location: include/crypto/skcipher.h:457
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_dec_hash_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8130f8d6)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
```
```
In fs/crypto/fname.c (ffffffff8130fefa)
Location: include/crypto/skcipher.h:514
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0f66)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:crypt_scatterlist
```
```
In fs/ecryptfs/keystore.c (ffffffff813d3697)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140b220)
Location: include/crypto/skcipher.h:514
Inline: True
```
```
In crypto/cts.c (ffffffff814874be)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
```
```
In crypto/xts.c (ffffffff814878be)
Location: include/crypto/skcipher.h:514
Inline: True
```
```
In crypto/gcm.c (ffffffff81489239)
Location: include/crypto/skcipher.h:514
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_dec_hash_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a8b60)
Location: crypto/skcipher.c:857
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
ffffffff814a8b60-ffffffff814a8bbc: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c37c0)
Location: crypto/skcipher.c:861
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
ffffffff814c37c0-ffffffff814c381c: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815229c0)
Location: crypto/skcipher.c:641
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/xts.c:decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
```
**Symbols:**

```
ffffffff815229c0-ffffffff81522a20: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153f880)
Location: crypto/skcipher.c:641
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/xts.c:xts_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
```
**Symbols:**

```
ffffffff8153f880-ffffffff8153f8e0: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81547e10)
Location: crypto/skcipher.c:636
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/xts.c:xts_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
```
**Symbols:**

```
ffffffff81547e10-ffffffff81547e70: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a85f0)
Location: crypto/skcipher.c:636
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/xts.c:xts_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
```
**Symbols:**

```
ffffffff815a85f0-ffffffff815a8650: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8164f980)
Location: crypto/skcipher.c:636
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/xts.c:xts_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
```
**Symbols:**

```
ffffffff8164f980-ffffffff8164f9e7: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81708dc0)
Location: crypto/skcipher.c:636
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/xts.c:xts_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
```
**Symbols:**

```
ffffffff81708dc0-ffffffff81708e27: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81742fe0)
Location: crypto/skcipher.c:659
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/xts.c:xts_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
```
**Symbols:**

```
ffffffff81742fe0-ffffffff81743040: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81785330)
Location: crypto/skcipher.c:677
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_data_unit
  - fs/crypto/fname.c:fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/xts.c:xts_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
```
**Symbols:**

```
ffffffff81785330-ffffffff817853a4: crypto_skcipher_decrypt (STB_GLOBAL)
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
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105be058)
Location: crypto/skcipher.c:861
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
ffff8000105be058-ffff8000105be0cc: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076be4c)
Location: crypto/skcipher.c:861
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
c076be4c-c076beb4: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c0000000007456c0)
Location: crypto/skcipher.c:861
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
c0000000007456c0-c000000000745778: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe000403504)
Location: crypto/skcipher.c:861
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
ffffffe000403504-ffffffe00040356e: crypto_skcipher_decrypt (STB_GLOBAL)
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
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bbda0)
Location: crypto/skcipher.c:861
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
ffffffff814bbda0-ffffffff814bbdfc: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814ac7c0)
Location: crypto/skcipher.c:861
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
ffffffff814ac7c0-ffffffff814ac81c: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b7e30)
Location: crypto/skcipher.c:861
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
ffffffff814b7e30-ffffffff814b7e8c: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_skcipher_decrypt(struct skcipher_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d0910)
Location: crypto/skcipher.c:861
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:crypto_cts_decrypt
  - crypto/cts.c:cts_cbc_decrypt
  - crypto/gcm.c:gcm_dec_hash_continue
```
**Symbols:**

```
ffffffff814d0910-ffffffff814d096c: crypto_skcipher_decrypt (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
