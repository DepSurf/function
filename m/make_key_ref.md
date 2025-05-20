# Function: <code>make_key_ref</code>

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
In certs/system_keyring.c (0)
Location: include/linux/key.h:113
Inline: True
```
```
In security/keys/key.c (ffffffff81330731)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81331809)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
```
```
In security/keys/process_keys.c (ffffffff81334084)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff813360ec)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81336449)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (0)
Location: include/linux/key.h:113
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (0)
Location: include/linux/key.h:113
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/linux/key.h:113
Inline: True
```
```
In lib/digsig.c (0)
Location: include/linux/key.h:113
Inline: True
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
In certs/system_keyring.c (ffffffff81fb0000)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In security/keys/key.c (ffffffff81365489)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813665ac)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff81368f85)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
```
```
In security/keys/proc.c (ffffffff8136b0c8)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8136b2f2)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff81fc48e0)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff813d25af)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff813effb9)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/efi_parser.c (ffffffff81fc582a)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list
```
```
In lib/digsig.c (ffffffff814614db)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff81fec6cf)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In security/keys/key.c (ffffffff8137bca9)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8137cdcc)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff8137f795)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
```
```
In security/keys/proc.c (ffffffff813818d8)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81381b02)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff82001317)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff813e9ccf)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81409839)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/efi_parser.c (ffffffff8200223a)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list
```
```
In lib/digsig.c (ffffffff8147fffb)
Location: include/linux/key.h:113
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff820cd5e1)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
```
```
In certs/blacklist.c (ffffffff811b5743)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In security/keys/key.c (ffffffff8138f878)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81390b4c)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff8139369b)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
```
```
In security/keys/proc.c (ffffffff81395808)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81395a37)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff820e4b92)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff813f60ca)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81416d9f)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8148929a)
Location: include/linux/key.h:114
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff826d6011)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
```
```
In certs/blacklist.c (ffffffff811c9833)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In security/keys/key.c (ffffffff813b4de7)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813b60f5)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff813b8d2c)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
```
```
In security/keys/request_key.c (ffffffff813b9a12)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff813baf63)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff813bb1b7)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff826ed799)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8141e1ca)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814417da)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff814c53da)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff827003c6)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
```
```
In certs/blacklist.c (ffffffff811ea988)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In security/keys/key.c (ffffffff813e54c9)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813e68f7)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff813e9abb)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
```
```
In security/keys/request_key.c (ffffffff813ea7b0)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff813ebd82)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff813ebf91)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff82717b39)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff81450473)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8147467f)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff814f62b4)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff828b7514)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
```
```
In certs/blacklist.c (ffffffff811fb4f8)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In security/keys/key.c (ffffffff813ffc99)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814010f7)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff814045d9)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
  - security/keys/process_keys.c:search_my_process_keyrings
```
```
In security/keys/request_key.c (ffffffff814051cc)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff8140698d)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81406b91)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828cf551)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8146d413)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814922bf)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8150a6b4)
Location: include/linux/key.h:115
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff828d0aea)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81212bee)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In security/keys/key.c (ffffffff8142c38b)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8142d937)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff814312c9)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff81432211)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (ffffffff81433abe)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81433d32)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828e9078)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8149ab05)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814bffcd)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff81539203)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff828d8f68)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff8122040e)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8134c1b5)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff814460db)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81447687)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff8144b029)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff8144bf71)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (ffffffff8144d82e)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8144daa2)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828f1c65)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814b4d55)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d8e1d)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8155a023)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff82cf861d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff8124d82d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff81391e50)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff814973ef)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81498e08)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff8149cc1d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff8149de6d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
```
```
In security/keys/proc.c (ffffffff8149f4aa)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8149f921)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff82d06cbc)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8151425d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8153808f)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff815e3953)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff82fe5316)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81257c6d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813a31ed)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff814b4e94)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814b6888)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff814ba6bd)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff814bb94d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
```
```
In security/keys/proc.c (ffffffff814bcee8)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff814bd351)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff82ff40e0)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff815313be)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81554eef)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff81607de3)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/common.c (ffffffff8125c086)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - certs/common.c:load_certificate_list
```
```
In certs/blacklist.c (ffffffff8125c2d5)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813aa42d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff814bace4)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814bc6d8)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff814c053d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff814c1815)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
```
```
In security/keys/proc.c (ffffffff814c2d86)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff814c31c2)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff831febb6)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff815397ee)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8155d66e)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff815eaaf3)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/common.c (ffffffff81297f36)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - certs/common.c:load_certificate_list
```
```
In certs/blacklist.c (ffffffff81298185)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813f9c7d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff81513514)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff815150f8)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff81518f5d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff8151a285)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
```
```
In security/keys/proc.c (ffffffff8151b776)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8151bbb2)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff832e5efd)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8159813b)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff815be98b)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff81656ff3)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/blacklist.c (ffffffff812ee715)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8146cf8e)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff815a5980)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff815a7888)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff815abb6f)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff815ad00d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
```
```
In security/keys/proc.c (ffffffff815ae9ab)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff815aee02)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff8349cd7d)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8163c9ba)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8166833b)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff8166b756)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In lib/digsig.c (ffffffff8176e831)
Location: include/linux/key.h:149
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/blacklist.c (ffffffff83eba289)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/blacklist.c:blacklist_init
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff814fe531)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
```
```
In security/keys/key.c (ffffffff8164f780)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff816518d8)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff81655fef)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff8165753d)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
```
```
In security/keys/proc.c (ffffffff8165911b)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff816595c2)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff83ed463a)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff816f4261)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff817229eb)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff8172632e)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In lib/digsig.c (ffffffff8189e121)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/blacklist.c (ffffffff8138a515)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_raw_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff81535b71)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
```
```
In security/keys/key.c (ffffffff81687ff7)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8168a188)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff8168e84f)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff8168fdd4)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
```
```
In security/keys/proc.c (ffffffff816919b5)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81691e53)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff836f977a)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8172e38a)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8175ed62)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff817626be)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In lib/digsig.c (ffffffff818e06e1)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff83911ed5)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/system_keyring.c:add_to_secondary_keyring
```
```
In certs/blacklist.c (ffffffff813b4035)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_raw_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8156ab41)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - fs/crypto/keyring.c:find_master_key_user
```
```
In security/keys/key.c (ffffffff816c4517)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyring.c (ffffffff816c6688)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff816cada1)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff816cc364)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_get_dest_keyring
```
```
In security/keys/proc.c (ffffffff816cdf8f)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff816ce423)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff8392cbe8)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8176ecea)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff817a0552)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff817a417e)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In block/sed-opal.c (ffffffff83931fbe)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - block/sed-opal.c:sed_opal_init
  - block/sed-opal.c:sed_ioctl
```
```
In lib/digsig.c (ffffffff81927221)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffff800011451b1c)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffff8000102ad6cc)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffff80001040cd4c)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffff80001052f2a4)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffff800010530eb4)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffff800010534d7c)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffff800010535cac)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (ffff80001053777c)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffff800010537c34)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffff80001146bf88)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffff8000105acf20)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffff8000105d496c)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffff800010666810)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (c152c518)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (c04da044)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (c05d9da4)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (c06e75d8)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (c06e8cf4)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (c06ec480)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (c06ecec8)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (c06ee7e4)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (c06eea3c)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (c1544c44)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (c075c79c)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (c07822e4)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (c080f474)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (c00000000137962c)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (c000000000361404)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (c00000000051a0cc)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (c00000000067bf60)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (c00000000067e198)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (c000000000683234)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (c000000000683fb0)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (c000000000686954)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (c000000000686ce0)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (c00000000139ace4)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (c00000000072b4e4)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (c000000000762fdc)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (c00000000081c3bc)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffe000011162)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffe0001d3b58)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffe0002b65ac)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffe000390ab8)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffe000391fb2)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffe000394e26)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffe000395638)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (ffffffe000396bac)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffe000396e14)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffe000026f34)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffe0003f554e)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffe000418c80)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffe000492918)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff828c1e19)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81218a5e)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff81344795)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff8143e6bb)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8143fc67)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff81443609)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff81444551)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (ffffffff81445e0e)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81446082)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828dab19)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814ad335)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d13fd)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff81552603)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff828ba541)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff8120bc6e)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff81335475)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff8142f12b)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814306d7)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff81434059)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff81434fa1)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (ffffffff8143685e)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81436ad2)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828d3235)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8149dd55)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814c1e1d)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff815428e3)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff828d4b9c)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff812167fe)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff81342265)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff8143a85b)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8143be07)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff8143f7a9)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff81440611)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (ffffffff81441eae)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81442122)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828ed88d)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814a93d5)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814cd48d)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8154e343)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff828d9fbd)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff8122587e)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
  - certs/blacklist.c:mark_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff81355565)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff8145199b)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81452f87)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:search_nested_keyrings
  - security/keys/keyring.c:keyring_search_iterator
  - security/keys/keyring.c:keyring_search_iterator
```
```
In security/keys/process_keys.c (ffffffff81456949)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:search_cred_keyrings_rcu
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff81457894)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/proc.c (ffffffff814591f9)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81459452)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828f2caf)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814c1de5)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814e5f5d)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff81568193)
Location: include/linux/key.h:132
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
</details>
</li>
</ul>

## Differences
