# Function: <code>key_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8132fbf0)
Location: security/keys/key.c:600
Inline: True
Direct callers:
  - kernel/user.c:free_uid
  - kernel/user.c:free_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - fs/ext4/crypto_key.c:ext4_free_crypt_info
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/x509_public_key.c:x509_request_asymmetric_key
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8132fbf0-ffffffff8132fc1f: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81364940)
Location: security/keys/key.c:619
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - kernel/user.c:free_uid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - fs/crypto/keyinfo.c:put_crypt_info
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:mpi_from_key
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81364940-ffffffff8136496f: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137b160)
Location: security/keys/key.c:619
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - kernel/user.c:free_uid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:mpi_from_key
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8137b160-ffffffff8137b18f: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138ed30)
Location: security/keys/key.c:624
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - kernel/user.c:free_uid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/request_key_auth.c:request_key_auth_destroy
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8138ed30-ffffffff8138ed5f: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b41f0)
Location: security/keys/key.c:633
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - kernel/user.c:free_uid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813b41f0-ffffffff813b4227: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813e48a0)
Location: security/keys/key.c:633
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - kernel/user.c:free_uid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key.c:complete_request_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_load_x509
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813e48a0-ffffffff813e48d6: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813ff0b0)
Location: security/keys/key.c:634
Inline: True
Direct callers:
  - kernel/user.c:alloc_uid
  - kernel/user.c:alloc_uid
  - kernel/user.c:free_uid
  - kernel/user.c:free_uid
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813ff0b0-ffffffff813ff0e6: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142b280)
Location: security/keys/key.c:641
Inline: True
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8142b280-ffffffff8142b2b4: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81444fd0)
Location: security/keys/key.c:641
Inline: True
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81444fd0-ffffffff81445004: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff8149741e)
Location: security/keys/key.c:644
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81495ec0-ffffffff81495f03: key_put.part.0 (STB_LOCAL)
ffffffff81495f10-ffffffff81495f59: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff814b4ec3)
Location: security/keys/key.c:647
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:pki_encrypt_session_key
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_key_revalidate
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814b3920-ffffffff814b3963: key_put.part.0 (STB_LOCAL)
ffffffff814b3970-ffffffff814b39b9: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff814bad13)
Location: security/keys/key.c:647
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/common.c:load_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814b9750-ffffffff814b9793: key_put.part.0 (STB_LOCAL)
ffffffff814b97a0-ffffffff814b97e9: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffff81513543)
Location: security/keys/key.c:647
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_work
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/common.c:load_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81511f80-ffffffff81511fc3: key_put.part.0 (STB_LOCAL)
ffffffff81511fd0-ffffffff81512019: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff815a4410)
Location: security/keys/key.c:647
Inline: True
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:fscrypt_key_destroy
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup.c:setup_file_encryption_key
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff815a4410-ffffffff815a4489: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8164e180)
Location: security/keys/key.c:647
Inline: True
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/trace/bpf_trace.c:bpf_key_put
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:get_keyring_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8164e180-ffffffff8164e1f9: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816869e0)
Location: security/keys/key.c:647
Inline: True
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/entry/common.c:exit_to_user_mode_loop
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/trace/bpf_trace.c:bpf_key_put
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:get_keyring_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff816869e0-ffffffff81686a59: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c2ef0)
Location: security/keys/key.c:644
Inline: True
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
  - kernel/entry/kvm.c:xfer_to_guest_mode_handle_work
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - kernel/trace/bpf_trace.c:bpf_key_put
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
  - certs/system_keyring.c:add_to_secondary_keyring
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:get_keyring_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:write_tag_1_packet
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_alloc_key
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_key_decrypt
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:security_overwrite
  - drivers/nvdimm/security.c:security_erase
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_update
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:security_disable
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:__nvdimm_security_unlock
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff816c2ef0-ffffffff816c2f69: key_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffff80001052ddc8)
Location: security/keys/key.c:641
Inline: True
Direct callers:
  - arch/arm64/kernel/signal.c:do_notify_resume
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__arm64_sys_request_key
  - security/keys/keyctl.c:__arm64_sys_request_key
  - security/keys/keyctl.c:__arm64_sys_add_key
  - security/keys/keyctl.c:__arm64_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffff80001052ddc8-ffff80001052de24: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c06e65b4)
Location: security/keys/key.c:641
Inline: True
Direct callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:set_cred_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c06e65b4-c06e65fc: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c00000000067a4e0)
Location: security/keys/key.c:641
Inline: True
Direct callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c00000000067a4e0-c00000000067a558: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/key.c (ffffffe000390af8)
Location: security/keys/key.c:641
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
Direct callers:
  - arch/riscv/kernel/signal.c:do_notify_resume
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffe00038f8ec-ffffffe00038f920: key_put.part.0 (STB_LOCAL)
ffffffe00038f920-ffffffe00038f962: key_put (STB_GLOBAL)
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
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8143d5b0)
Location: security/keys/key.c:641
Inline: True
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8143d5b0-ffffffff8143d5e4: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8142e020)
Location: security/keys/key.c:641
Inline: True
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8142e020-ffffffff8142e054: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81439750)
Location: security/keys/key.c:641
Inline: True
Direct callers:
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81439750-ffffffff81439784: key_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void key_put(struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff814509c0)
Location: security/keys/key.c:641
Inline: True
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/cred.c:copy_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:prepare_exec_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:create_user_ns
  - kernel/user_namespace.c:create_user_ns
  - certs/system_keyring.c:load_system_certificate_list
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:fscrypt_ioctl_get_key_status
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:fscrypt_verify_key_added
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key_user
  - fs/crypto/keyring.c:fscrypt_sb_free
  - fs/crypto/keyring.c:free_master_key
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
  - fs/crypto/keysetup.c:put_crypt_info
  - fs/crypto/keysetup_v1.c:fscrypt_setup_v1_file_key_via_subscribed_keyrings
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/verity/signature.c:fsverity_init_signature
  - fs/ecryptfs/crypto.c:ecryptfs_destroy_mount_crypt_stat
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_generate_key_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/keyring.c:keyring_restriction_gc
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_alloc
  - security/keys/keyring.c:keyring_destroy
  - security/keys/keyring.c:keyring_free_object
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyring.c:key_free_user_ns
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_reject_key
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_instantiate_key_common
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:request_key_with_auxdata
  - security/keys/request_key.c:request_key_tag
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:umh_keys_cleanup
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/proc.c:proc_keys_show
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_verify
  - security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s
  - security/keys/keyctl_pkey.c:keyctl_pkey_query
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_read
  - security/keys/encrypted-keys/encrypted.c:encrypted_instantiate
  - security/integrity/digsig.c:integrity_add_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - lib/digsig.c:digsig_verify
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_key.c:init_dns_resolver
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814509c0-ffffffff814509f4: key_put (STB_GLOBAL)
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
