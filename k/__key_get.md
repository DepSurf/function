# Function: <code>__key_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a248e)
Location: include/linux/key.h:226
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff81307c90)
Location: include/linux/key.h:226
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/key.c (ffffffff81330323)
Location: include/linux/key.h:226
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8133097a)
Location: include/linux/key.h:226
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:__key_link
```
```
In security/keys/keyctl.c (ffffffff81331cca)
Location: include/linux/key.h:226
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81333ad0)
Location: include/linux/key.h:226
Inline: True
Inline callers:
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81334634)
Location: include/linux/key.h:226
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff81335420)
Location: include/linux/key.h:226
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a5bde)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff8133bb40)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/key.c (ffffffff81365073)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff813656fa)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (ffffffff81366a8a)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff813694eb)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff81369e98)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8136a39e)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810ab83e)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813518d0)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/key.c (ffffffff8137b893)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/key.c:key_lookup
```
```
In security/keys/keyring.c (ffffffff8137bf1a)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (ffffffff8137d2aa)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff8137fcfb)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff813806a8)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81380bae)
Location: include/linux/key.h:243
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810a843e)
Location: include/linux/key.h:251
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813663fb)
Location: include/linux/key.h:251
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8138fab8)
Location: include/linux/key.h:251
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (ffffffff8139109a)
Location: include/linux/key.h:251
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81393b7b)
Location: include/linux/key.h:251
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8139449c)
Location: include/linux/key.h:251
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81394a1f)
Location: include/linux/key.h:251
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff814176eb)
Location: include/linux/key.h:251
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct key *__key_get(struct key *key);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810aebbe)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff8138b068)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff813b5f23)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (ffffffff813b676a)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff813b920b)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff813b97e0)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
Direct callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff813ba1a5)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff81442174)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
**Symbols:**

```
ffffffff813b9260-ffffffff813b9272: __key_get (STB_LOCAL)
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
In kernel/cred.c (ffffffff810b594e)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813b9f35)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff813e6717)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (ffffffff813e731a)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff813e9f9b)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff813ea550)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff813eae9b)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff81474fb4)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
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
In kernel/cred.c (ffffffff810be974)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813d34e5)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81400f07)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (ffffffff81401b1a)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff814049e1)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff81404fc2)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff814058d2)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff81492bf4)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c4c10)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813fdfb8)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8142d02e)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8142e62a)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81431892)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff81431f41)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff814329b2)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff814c02e0)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cdd20)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff8134de62)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81417ea8)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81446d7e)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff814483da)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff8144b5f2)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8144bca1)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff8144c722)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff814d9130)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d7768)
Location: include/linux/key.h:299
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff81393cf7)
Location: include/linux/key.h:299
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff8146640e)
Location: include/linux/key.h:299
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8149860a)
Location: include/linux/key.h:299
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81499816)
Location: include/linux/key.h:299
Inline: True
```
```
In security/keys/process_keys.c (ffffffff8149d320)
Location: include/linux/key.h:299
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8149d91b)
Location: include/linux/key.h:299
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
```
```
In security/keys/request_key_auth.c (ffffffff8149e782)
Location: include/linux/key.h:299
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff815389ed)
Location: include/linux/key.h:299
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d258c)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff813a51b7)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff8148189e)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff814b607a)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff814b72a6)
Location: include/linux/key.h:300
Inline: True
```
```
In security/keys/process_keys.c (ffffffff814badf5)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff814bb927)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff814bc272)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff815557ed)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d4164)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff813ac2a3)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff814872fe)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff814bbeea)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff814bd106)
Location: include/linux/key.h:300
Inline: True
```
```
In security/keys/process_keys.c (ffffffff814c0cc3)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff814c17f3)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff814c213f)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff8155df6d)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e72e4)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff813fbbdd)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff814dea9e)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8151475f)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81515b86)
Location: include/linux/key.h:300
Inline: True
```
```
In security/keys/process_keys.c (ffffffff81519705)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8151a263)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff8151ab2f)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff815bf27d)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81101571)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff8146efb9)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff8156ca9b)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff815a6dd8)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff815a8397)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff815ac2d5)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff815acfeb)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff815ada17)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff81669088)
Location: include/linux/key.h:300
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81126721)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff81610ea9)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81650d98)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff816524a7)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff81656765)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8165751b)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff81658077)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff817238d8)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81133bd1)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff81648d59)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81689678)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8168acc7)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff8168efa5)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff8168fe17)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff816908f5)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff8175fbd8)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113ee1b)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff81682229)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff816c5b89)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff816c71c7)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff816cb511)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff816cc3a7)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff816cceb3)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff817a1468)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffff80001012cfa4)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffff80001040f168)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffff8000104f9724)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffff80001052fda0)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffff8000105318d8)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffff800010535250)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffff800010535a18)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffff8000105366a8)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffff8000105d516c)
Location: include/linux/key.h:279
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c037d418)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (c05dbcd0)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (c06b6f80)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (c06e7ffc)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (c06e958c)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (c06ec960)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (c06ecc7c)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (c06edb90)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (c0782aa8)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c000000000175e80)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (c00000000051c9c4)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (c00000000063bb40)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (c00000000067c590)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (c00000000067f04c)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (c000000000683820)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (c000000000683c84)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (c00000000068507c)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (c0000000007633ec)
Location: include/linux/key.h:279
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffe0000e198a)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffe0002b7eda)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffe000367e0e)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffe000390fd6)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffe000392798)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffe0003951e0)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffe0003953ea)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffe00039613a)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffe000419456)
Location: include/linux/key.h:279
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c80a0)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff81346442)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81410488)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8143f35e)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff814409ba)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81443bd2)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff81444281)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff81444d02)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff814d1710)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b68c0)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff81337122)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81400f08)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8142fdce)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8143142a)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81434622)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff81434cd1)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff81435752)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff814c2130)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c75f0)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff81343f12)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff8140d808)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8143b4fe)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff8143cb5a)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff8143fd72)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff81440341)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81440da2)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff814cd7a0)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cfac0)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff813571f2)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81423478)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8145264e)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
  - security/keys/keyring.c:__key_link
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_rcu
```
```
In security/keys/keyctl.c (ffffffff81453cea)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81456f22)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
```
```
In security/keys/request_key.c (ffffffff814575c2)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff81458092)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In crypto/asymmetric_keys/restrict.c (ffffffff814e6270)
Location: include/linux/key.h:279
Inline: True
Inline callers:
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
