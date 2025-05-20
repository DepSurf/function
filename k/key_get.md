# Function: <code>key_get</code>

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
In kernel/cred.c (ffffffff810a2489)
Location: include/linux/key.h:232
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff81307c84)
Location: include/linux/key.h:232
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81330975)
Location: include/linux/key.h:232
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff81331cc5)
Location: include/linux/key.h:232
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81334556)
Location: include/linux/key.h:232
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81334634)
Location: include/linux/key.h:232
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff8133541b)
Location: include/linux/key.h:232
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
In kernel/cred.c (ffffffff810a5bd9)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff8133bb34)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff813656f5)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff81366a85)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff813694e6)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81369e93)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff8136a399)
Location: include/linux/key.h:249
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
In kernel/cred.c (ffffffff810ab839)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813518c4)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8137bf15)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff8137d2a5)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff8137fcf6)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff813806a3)
Location: include/linux/key.h:249
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81380ba9)
Location: include/linux/key.h:249
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
In kernel/cred.c (ffffffff810a8439)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813663ef)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8138fab3)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff81391095)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81393b76)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81394497)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81394a1a)
Location: include/linux/key.h:257
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810aebb9)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff8138b05c)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff813b5f12)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff813b6765)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff813b9206)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff813b97e0)
Location: include/linux/key.h:263
Inline: True
Inline callers:
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
```
```
In security/keys/request_key_auth.c (ffffffff813ba1a0)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810b5949)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813b9f30)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff813e6712)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff813e7315)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff813e9f96)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff813ea550)
Location: include/linux/key.h:263
Inline: True
Inline callers:
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
```
```
In security/keys/request_key_auth.c (ffffffff813eae96)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810be96f)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813d34e0)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81400f02)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff81401b15)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff814049dc)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81404fc2)
Location: include/linux/key.h:263
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
In security/keys/request_key_auth.c (ffffffff814058cd)
Location: include/linux/key.h:263
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810c4c0b)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff813fdfb3)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8142d029)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff8142e625)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff8143188d)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81431f41)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff814329ad)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810cdd1b)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff8134de62)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81417ea3)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81446d79)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff814483d5)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff8144b5ed)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff8144bca1)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff8144c71d)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810d7763)
Location: include/linux/key.h:305
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff81393cf2)
Location: include/linux/key.h:305
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81466409)
Location: include/linux/key.h:305
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81498605)
Location: include/linux/key.h:305
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff81499811)
Location: include/linux/key.h:305
Inline: True
```
```
In security/keys/process_keys.c (ffffffff8149d31b)
Location: include/linux/key.h:305
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff8149d91b)
Location: include/linux/key.h:305
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
```
```
In security/keys/request_key_auth.c (ffffffff8149e77d)
Location: include/linux/key.h:305
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810d2587)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff813a51b2)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81481899)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff814b6075)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff814b72a1)
Location: include/linux/key.h:306
Inline: True
```
```
In security/keys/process_keys.c (ffffffff814badf0)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff814bb91e)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff814bc26d)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810d415f)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff813ac29e)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff814872f9)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff814bbee5)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff814bd101)
Location: include/linux/key.h:306
Inline: True
```
```
In security/keys/process_keys.c (ffffffff814c0cbe)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff814c17ea)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff814c213a)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810e72df)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff813fbbd8)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff814dea99)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8151475a)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff81515b81)
Location: include/linux/key.h:306
Inline: True
```
```
In security/keys/process_keys.c (ffffffff81519700)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff8151a25a)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff8151ab2a)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff8110156c)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff8146efb4)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff8156ca96)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff815a6dd2)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff815a8392)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff815ac2d0)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff815acfe2)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff815ada12)
Location: include/linux/key.h:306
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff8112671c)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff81610ea4)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81650d92)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff816524a2)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff81656760)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81657512)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff81658072)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff81133bcc)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff81648d54)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81689672)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff8168acc2)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff8168efa0)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff8168fe12)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff816908f0)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff8113ee16)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/ecryptfs/keystore.c (ffffffff81682224)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff816c5b83)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff816c71c2)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:get_instantiation_keyring
```
```
In security/keys/process_keys.c (ffffffff816cb50c)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff816cc3a2)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:construct_get_dest_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff816cceae)
Location: include/linux/key.h:312
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffff80001012cfa0)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffff80001040f168)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffff8000104f9720)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffff80001052fd9c)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffff8000105318d4)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffff80001053524c)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffff800010535a18)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffff8000105366a4)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (c037d410)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (c05dbcd0)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (c06b6f7c)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (c06e7ff4)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (c06e9584)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (c06ec958)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (c06ecc7c)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (c06edb88)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (c000000000175e78)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (c00000000051c9c4)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (c00000000063bb3c)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (c00000000067c588)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (c00000000067f044)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (c000000000683818)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (c000000000683c84)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (c000000000685074)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffe0000e1988)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffe0002b7eda)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffe000367e0c)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffe000390fd4)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffe000392794)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffe0003951de)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffe0003953e8)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffe000396136)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810c809b)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff81346442)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81410483)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8143f359)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff814409b5)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81443bcd)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81444281)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff81444cfd)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810b68bb)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff81337122)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81400f03)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8142fdc9)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff81431425)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff8143461d)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81434cd1)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff8143574d)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810c75eb)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff81343f12)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff8140d803)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff8143b4f9)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff8143cb55)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff8143fd6d)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff81440341)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffff81440d9d)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
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
In kernel/cred.c (ffffffff810cfabb)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:prepare_creds
```
```
In fs/crypto/keysetup.c (ffffffff813571f2)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
```
In fs/ecryptfs/keystore.c (ffffffff81423473)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
```
```
In security/keys/keyring.c (ffffffff81452649)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_gc_select_iterator
```
```
In security/keys/keyctl.c (ffffffff81453ce5)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_change_reqkey_auth
```
```
In security/keys/process_keys.c (ffffffff81456f1d)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:key_change_session_keyring
```
```
In security/keys/request_key.c (ffffffff814575c2)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:construct_key_and_link
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:cache_requested_key
  - security/keys/request_key.c:check_cached_key
```
```
In security/keys/request_key_auth.c (ffffffff8145808d)
Location: include/linux/key.h:285
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
  - security/keys/request_key_auth.c:request_key_auth_new
```
</details>
</li>
</ul>

## Differences
