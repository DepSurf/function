# Function: <code>kzfree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b2b70)
Location: mm/slab_common.c:1261
Inline: False
Direct callers:
  - fs/ext4/crypto.c:ext4_page_crypto
  - fs/ext4/crypto_key.c:ext4_derive_key_aes
  - fs/ext4/crypto_fname.c:ext4_fname_encrypt
  - fs/ext4/crypto_fname.c:ext4_fname_decrypt
  - fs/ext4/crypto_fname.c:ext4_fname_decrypt
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:aa_free_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/ahash.c:ahash_def_finup_finish2
  - crypto/shash.c:crypto_shash_setkey
  - crypto/shash.c:crypto_exit_shash_ops_compat
  - crypto/rng.c:crypto_rng_reset
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - lib/mpi/mpiutil.c:mpi_resize
  - net/core/sock.c:sock_kzfree_s
```
**Symbols:**

```
ffffffff811b2b70-ffffffff811b2ba1: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811cc5d0)
Location: mm/slab_common.c:1314
Inline: False
Direct callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/policy_ns.c:aa_free_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_destroy_tfm
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_def_finup_finish2
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
```
**Symbols:**

```
ffffffff811cc5d0-ffffffff811cc601: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dc6a0)
Location: mm/slab_common.c:1343
Inline: False
Direct callers:
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/context.c:aa_free_task_context
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/policy_ns.c:aa_free_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_destroy_tfm
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_def_finup_finish2
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
```
**Symbols:**

```
ffffffff811dc6a0-ffffffff811dc6d1: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e65d0)
Location: mm/slab_common.c:1431
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
```
**Symbols:**

```
ffffffff811e65d0-ffffffff811e6602: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fc810)
Location: mm/slab_common.c:1473
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_read
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
```
**Symbols:**

```
ffffffff811fc810-ffffffff811fc842: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121d970)
Location: mm/slab_common.c:1534
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/xts.c:do_decrypt
  - crypto/xts.c:do_encrypt
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
```
**Symbols:**

```
ffffffff8121d970-ffffffff8121d9a1: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81230960)
Location: mm/slab_common.c:1581
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/crypto.c:fscrypt_do_page_crypto
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/core/sock.c:sock_kzfree_s
```
**Symbols:**

```
ffffffff81230960-ffffffff81230991: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81240cf0)
Location: mm/slab_common.c:1671
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyinfo.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
ffffffff81240cf0-ffffffff81240d23: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8124f2a0)
Location: mm/slab_common.c:1735
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
ffffffff8124f2a0-ffffffff8124f2d3: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127d9d0)
Location: mm/slab_common.c:1721
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fscrypt_fname_encrypt
  - fs/crypto/keyring.c:fscrypt_provisioning_key_destroy
  - fs/crypto/keyring.c:fscrypt_provisioning_key_free_preparse
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:setup_v1_file_key_derived
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
  - fs/crypto/keysetup_v1.c:fscrypt_put_direct_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_destroy
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_update
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_rcu_free
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_instantiate
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_checkhmac1
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_authhmac
  - security/keys/trusted-keys/trusted_tpm1.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:calc_buffer_ahash_atfm
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey_unaligned
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:ahash_setkey_unaligned
  - crypto/shash.c:shash_setkey_unaligned
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - block/blk-crypto-fallback.c:blk_crypto_fallback_encrypt_bio
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
  - arch/x86/power/hibernate.c:get_e820_md5
```
**Symbols:**

```
ffffffff8127d9d0-ffffffff8127da1a: kzfree (STB_GLOBAL)
```
</details>
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
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e5640)
Location: mm/slab_common.c:1735
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
ffff8000102e5640-ffff8000102e568c: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c050a4c4)
Location: mm/slab_common.c:1735
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_decrypt
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/crypto.c:crypt_extent
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
c050a4c4-c050a504: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a7680)
Location: mm/slab_common.c:1735
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
c0000000003a7680-c0000000003a76e4: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fc0ce)
Location: mm/slab_common.c:1735
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:keyctl_dh_compute_kdf
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
ffffffe0001fc0ce-ffffffe0001fc116: kzfree (STB_GLOBAL)
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
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812478f0)
Location: mm/slab_common.c:1735
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
ffffffff812478f0-ffffffff81247923: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8123a8a0)
Location: mm/slab_common.c:1735
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
ffffffff8123a8a0-ffffffff8123a8d3: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81245690)
Location: mm/slab_common.c:1735
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
ffffffff81245690-ffffffff812456c3: kzfree (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kzfree(const void *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff812550a0)
Location: mm/slab_common.c:1735
Inline: False
Direct callers:
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/crypto.c:fscrypt_crypt_block
  - fs/crypto/fname.c:fname_encrypt
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key
  - fs/crypto/keysetup_v1.c:derive_key_aes
  - fs/verity/enable.c:build_merkle_tree
  - fs/verity/hash_algs.c:fsverity_hash_buffer
  - fs/verity/hash_algs.c:fsverity_prepare_hash_state
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_page
  - fs/ecryptfs/crypto.c:crypt_scatterlist
  - fs/ecryptfs/keystore.c:write_tag_3_packet
  - fs/ecryptfs/keystore.c:decrypt_passphrase_encrypted_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/messaging.c:ecryptfs_exorcise_daemon
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/user_defined.c:user_destroy
  - security/keys/user_defined.c:user_free_payload_rcu
  - security/keys/user_defined.c:user_free_preparse
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/dh.c:__keyctl_dh_compute
  - security/keys/big_key.c:big_key_destroy
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_free_preparse
  - security/keys/big_key.c:big_key_preparse
  - security/keys/big_key.c:big_key_crypt
  - security/keys/trusted.c:trusted_destroy
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_read
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_update
  - security/keys/trusted.c:trusted_rcu_free
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:trusted_instantiate
  - security/keys/trusted.c:key_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:tpm_seal
  - security/keys/trusted.c:TSS_checkhmac1
  - security/keys/trusted.c:TSS_authhmac
  - security/keys/trusted.c:TSS_rawhmac
  - security/keys/encrypted-keys/encrypted.c:encrypted_destroy
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_update
  - security/keys/encrypted-keys/encrypted.c:encrypted_rcu_free
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:get_derived_key
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/domain.c:aa_free_domain_entries
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy.c:aa_free_data
  - security/apparmor/policy_unpack.c:aa_load_ent_free
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_unpack.c:do_loaddata_free
  - security/apparmor/policy_ns.c:alloc_ns
  - security/apparmor/policy_ns.c:alloc_ns
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_atfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/skcipher.c:skcipher_setkey
  - crypto/seqiv.c:seqiv_aead_encrypt_complete2
  - crypto/ahash.c:ahash_restore_req
  - crypto/ahash.c:crypto_ahash_setkey
  - crypto/shash.c:crypto_shash_setkey
  - crypto/rsa-pkcs1pad.c:pkcs1pad_verify_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_decrypt_complete
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt_sign_complete
  - crypto/acompress.c:acomp_request_free
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gf128mul.c:gf128mul_free_64k
  - crypto/gcm.c:crypto_gcm_setkey
  - crypto/deflate.c:deflate_free_ctx
  - crypto/rng.c:crypto_rng_reset
  - crypto/drbg.c:drbg_fini_sym_kernel
  - crypto/drbg.c:drbg_fini_hash_kernel
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_uninstantiate
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/drbg.c:drbg_alloc_state
  - crypto/jitterentropy-kcapi.c:jent_zfree
  - crypto/ghash-generic.c:ghash_exit_tfm
  - crypto/ghash-generic.c:ghash_setkey
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:public_key_verify_signature
  - crypto/asymmetric_keys/public_key.c:software_key_eds_op
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
  - lib/mpi/mpiutil.c:mpi_free
  - lib/mpi/mpiutil.c:mpi_resize
  - lib/mpi/mpiutil.c:mpi_assign_limb_space
  - arch/x86/power/hibernate.c:get_e820_md5
  - net/core/sock.c:sock_kzfree_s
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_ctx_free
```
**Symbols:**

```
ffffffff812550a0-ffffffff812550d3: kzfree (STB_GLOBAL)
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
