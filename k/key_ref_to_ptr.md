# Function: <code>key_ref_to_ptr</code>

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
In certs/system_keyring.c (ffffffff81f86876)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In security/keys/key.c (ffffffff8132f9b5)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81331672)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_search_aux
```
```
In security/keys/keyctl.c (ffffffff81331ed3)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_get_security
```
```
In security/keys/permission.c (ffffffff8133373e)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (0)
Location: include/linux/key.h:119
Inline: True
```
```
In security/keys/request_key.c (ffffffff81334b37)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff813355fa)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (0)
Location: include/linux/key.h:119
Inline: True
```
```
In security/keys/persistent.c (ffffffff8133627e)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/selinux/hooks.c (0)
Location: include/linux/key.h:119
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/key.h:119
Inline: True
```
```
In security/integrity/digsig.c (ffffffff81f99ba8)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff81396843)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff813ad980)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_request_asymmetric_key
```
```
In lib/digsig.c (ffffffff81419795)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
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
In certs/system_keyring.c (ffffffff81fb005e)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In security/keys/key.c (ffffffff81364705)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81366587)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff813682f7)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
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
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/keys/permission.c (ffffffff813685ce)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff8136924c)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81369ae4)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff8136a57a)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff8136b0bc)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8136b251)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff8136b4d7)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/dh.c:mpi_from_key
```
```
In security/selinux/hooks.c (ffffffff8137b91c)
Location: include/linux/key.h:119
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/key.h:119
Inline: True
```
```
In security/integrity/digsig.c (ffffffff81fc4925)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff813d2654)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff813effe7)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/efi_parser.c (ffffffff81fc597e)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list
```
```
In lib/digsig.c (ffffffff814614fe)
Location: include/linux/key.h:119
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
In certs/system_keyring.c (ffffffff81fec72d)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In security/keys/key.c (ffffffff8137af25)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8137cda7)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff8137eb07)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
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
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/keys/permission.c (ffffffff8137edde)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff8137fa5c)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813802f4)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff81380d8a)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff813818cc)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81381a61)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff81381ce7)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/keys/dh.c:mpi_from_key
```
```
In security/selinux/hooks.c (ffffffff81391d5c)
Location: include/linux/key.h:119
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/key.h:119
Inline: True
```
```
In security/integrity/digsig.c (ffffffff8200135c)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff813e9cf6)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81409867)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/efi_parser.c (ffffffff8200238e)
Location: include/linux/key.h:119
Inline: True
Inline callers:
  - crypto/asymmetric_keys/efi_parser.c:parse_efi_signature_list
```
```
In lib/digsig.c (ffffffff8148001e)
Location: include/linux/key.h:119
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
In certs/system_keyring.c (ffffffff820cd620)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
```
```
In certs/blacklist.c (ffffffff811b576a)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff8138eb3e)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81390b27)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff81392bda)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/keys/permission.c (ffffffff81392d3d)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff8139394a)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81394177)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff81394bc7)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff813957fc)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81395955)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff81395c20)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/selinux/hooks.c (ffffffff813a835e)
Location: include/linux/key.h:120
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/key.h:120
Inline: True
```
```
In security/integrity/digsig.c (ffffffff820e4bd7)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff813f60f0)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81416dc8)
Location: include/linux/key.h:120
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff814892c0)
Location: include/linux/key.h:120
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
In certs/system_keyring.c (ffffffff826d6050)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
```
```
In certs/blacklist.c (ffffffff811c985a)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff813b3fee)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813b60c7)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff813b8208)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/keys/permission.c (ffffffff813b839d)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff813b8faa)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813b9747)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff813ba2fe)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff813baf57)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff813bb0d5)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff813bb3a0)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/selinux/hooks.c (ffffffff813cdafe)
Location: include/linux/key.h:121
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/linux/key.h:121
Inline: True
```
```
In security/integrity/digsig.c (ffffffff826ed7df)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8141e1f0)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81441803)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff814c5400)
Location: include/linux/key.h:121
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
In certs/system_keyring.c (ffffffff82700405)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
```
```
In certs/blacklist.c (ffffffff811ea9c3)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff813e46a3)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff813e68b5)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff813e8e07)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/permission.c (ffffffff813e9105)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff813e9d44)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff813ea4f5)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff813eb00e)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff813ebd76)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff813ebeb5)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff813ec199)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/selinux/hooks.c (ffffffff813fb014)
Location: include/linux/key.h:121
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8141c124)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff82717b7f)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8145049a)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81474706)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff814f649e)
Location: include/linux/key.h:121
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
In certs/system_keyring.c (ffffffff828b7553)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
  - certs/system_keyring.c:add_trusted_secondary_key
```
```
In certs/blacklist.c (ffffffff811fb533)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff813fee93)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814010b5)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:keyring_search_aux
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff81403607)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/permission.c (ffffffff81403b35)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff81404631)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81404f67)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff81405a54)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff81406981)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81406ab5)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff81406d99)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff81407857)
Location: include/linux/key.h:121
Inline: True
```
```
In security/selinux/hooks.c (ffffffff814175e4)
Location: include/linux/key.h:121
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81438d98)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff828cf57e)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8146d43a)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81492346)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8150a89e)
Location: include/linux/key.h:121
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81703e88)
Location: include/linux/key.h:121
Inline: True
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
In certs/system_keyring.c (ffffffff828d0b2e)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81212c12)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff8142b063)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8142d8f5)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff81430250)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/permission.c (ffffffff814307a5)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff81431485)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff81431b53)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff81432b6e)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff81433ab2)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81433c35)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff81433f30)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff814349f9)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (ffffffff814451c4)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814669db)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff828e90ab)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8149ab31)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814c0004)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8153922e)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff8173db0e)
Location: include/linux/key.h:138
Inline: True
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
In certs/system_keyring.c (ffffffff828d8fac)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81220432)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8134c1cc)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff81444db3)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81447645)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff81449fb0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/permission.c (ffffffff8144a505)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff8144b1e5)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff8144b8b3)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff8144c8de)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff8144d822)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8144d9a5)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff8144dca0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff8144e779)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8145ed34)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814807bb)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff828f1c98)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814b4d81)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d8e54)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8155a04e)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff8176198e)
Location: include/linux/key.h:138
Inline: True
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
In certs/system_keyring.c (ffffffff82cf8661)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff8124d851)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813929ba)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff81496743)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81498db5)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff8149be49)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/permission.c (ffffffff8149c04c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff8149cdf2)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff8149d8f0)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
```
```
In security/keys/request_key_auth.c (ffffffff8149e9ae)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff8149f49a)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8149fb31)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/keys/dh.c (ffffffff8149fcc0)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff814a07e7)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In security/selinux/hooks.c (ffffffff814af45f)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
```
```
In security/smack/smack_lsm.c (ffffffff814d6a3c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff82d06cef)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff81514284)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff815380c6)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff815e397e)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff818215f0)
Location: include/linux/key.h:155
Inline: True
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
In certs/system_keyring.c (ffffffff82fe535a)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81257c91)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813a3d2a)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff814b41b3)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814b6835)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff814b98e9)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/permission.c (ffffffff814b9aec)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff814ba892)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff814bb413)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
```
```
In security/keys/request_key_auth.c (ffffffff814bc4ac)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff814bced8)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff814bd561)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/keys/dh.c (ffffffff814bd6d0)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff814be1b7)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In security/selinux/hooks.c (ffffffff814cceff)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
```
```
In security/smack/smack_lsm.c (ffffffff814f430c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff82ff4113)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff815313e9)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81554f26)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff81607e0e)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81830300)
Location: include/linux/key.h:155
Inline: True
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
In certs/common.c (ffffffff81bd8683)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/common.c:load_certificate_list
```
```
In certs/blacklist.c (ffffffff81bd86ff)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813aaf6a)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff814b9fe3)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff814bc685)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff814bf74c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/permission.c (ffffffff814bf96c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff814c070e)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff814c12d3)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
```
```
In security/keys/request_key_auth.c (ffffffff814c236c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff814c2d76)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff814c33d1)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/keys/dh.c (ffffffff814c3540)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff814c4001)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In security/selinux/hooks.c (ffffffff814d34ff)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
```
```
In security/smack/smack_lsm.c (ffffffff814fb28c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff831febe9)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff81539819)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8155d6a5)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff815eab1e)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81813591)
Location: include/linux/key.h:155
Inline: True
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
In certs/common.c (ffffffff81cb9cda)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/common.c:load_certificate_list
```
```
In certs/blacklist.c (ffffffff81cb9d56)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813fa7fa)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff81512813)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff815150a5)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff8151816c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/permission.c (ffffffff8151838c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff8151912e)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff81519d43)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
```
```
In security/keys/request_key_auth.c (ffffffff8151ad5c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff8151b766)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8151bdc1)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/keys/dh.c (ffffffff8151bf30)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff8151c9d1)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In security/selinux/hooks.c (ffffffff8152c1bf)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
```
```
In security/smack/smack_lsm.c (ffffffff81555efc)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff832e5f3b)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff81598166)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff815be9c2)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8165701e)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff8189dbc1)
Location: include/linux/key.h:155
Inline: True
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
In certs/blacklist.c (ffffffff81e6b344)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8146da64)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
```
```
In security/keys/key.c (ffffffff815a4d1a)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff815a7835)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff815aac1a)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/permission.c (ffffffff815aaeb5)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff815abd73)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff815ac9ef)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
```
```
In security/keys/request_key_auth.c (ffffffff815adc83)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff815ae99b)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff815af01e)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/keys/dh.c (ffffffff815af120)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff815afba6)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In security/selinux/hooks.c (ffffffff815c2271)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
```
```
In security/smack/smack_lsm.c (ffffffff815efead)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff8349cdba)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8163c9e5)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81668371)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff81e8aca0)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In lib/digsig.c (ffffffff8176e85c)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff819e765d)
Location: include/linux/key.h:155
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
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
In kernel/trace/bpf_trace.c (ffffffff812a96c6)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
```
```
In certs/blacklist.c (ffffffff81358c2d)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff814fe230)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - fs/crypto/keyring.c:get_keyring_key
  - fs/crypto/keyring.c:find_master_key_user
```
```
In security/keys/key.c (ffffffff8164e37a)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81651885)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff81654f9a)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/permission.c (ffffffff81655265)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff816561f3)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff81656eff)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
```
```
In security/keys/request_key_auth.c (ffffffff816582f3)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff8165910b)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff816597ee)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/keys/dh.c (ffffffff81659910)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff8165a3c6)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In security/selinux/hooks.c (ffffffff8166ea01)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
```
```
In security/smack/smack_lsm.c (ffffffff816a024d)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff83ed465d)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff816f428c)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff81722a21)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff817262d5)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In lib/digsig.c (ffffffff8189e14c)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81b6389d)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
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
In kernel/trace/bpf_trace.c (ffffffff812cbf46)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
```
```
In certs/blacklist.c (ffffffff8138a54d)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff81535810)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - fs/crypto/keyring.c:get_keyring_key
  - fs/crypto/keyring.c:find_master_key_user
```
```
In security/keys/key.c (ffffffff81686bda)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8168a135)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff8168d6b7)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/permission.c (ffffffff8168da8a)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff8168e88e)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff8168f79f)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
```
```
In security/keys/request_key_auth.c (ffffffff81690b73)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff816919a5)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8169208e)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/keys/dh.c (ffffffff81692170)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff81692ca6)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In security/selinux/hooks.c (ffffffff816a708e)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
```
```
In security/smack/smack_lsm.c (ffffffff816d4faa)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff836f979d)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8172e3b5)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff8175ed98)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff81762665)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In lib/digsig.c (ffffffff818e070c)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81bb6e9d)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
```
```
In net/handshake/tlshd.c (ffffffff82094127)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
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
In kernel/trace/bpf_trace.c (ffffffff812e9289)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
```
```
In certs/system_keyring.c (ffffffff83911f0d)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - certs/system_keyring.c:add_to_secondary_keyring
```
```
In certs/blacklist.c (ffffffff813b406d)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - certs/blacklist.c:add_key_to_revocation_list
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8156a7e0)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - fs/crypto/keyring.c:get_keyring_key
  - fs/crypto/keyring.c:find_master_key_user
```
```
In security/keys/key.c (ffffffff816c30ea)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyring.c (ffffffff816c6635)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff816c9c07)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/permission.c (ffffffff816c9fda)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff816cade0)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff816cbd2f)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_alloc_key
```
```
In security/keys/request_key_auth.c (ffffffff816cd143)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff816cdf7f)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff816ce65e)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/keys/dh.c (ffffffff816ce740)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff816cf276)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
```
In security/selinux/hooks.c (ffffffff816e3bb2)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_key_permission
```
```
In security/smack/smack_lsm.c (ffffffff817112bc)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff8392cc0b)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8176ed15)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff817a0588)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff817a4125)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In block/sed-opal.c (ffffffff81802626)
Location: include/linux/key.h:161
Inline: True
```
```
In lib/digsig.c (ffffffff8192724c)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81c0b4ed)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
```
```
In net/handshake/tlshd.c (ffffffff8216aa47)
Location: include/linux/key.h:161
Inline: True
Inline callers:
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
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
In certs/system_keyring.c (ffff800011451b84)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffff8000102ad6f0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffff80001040cd68)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffff80001052dba0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffff800010530e74)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffff800010533dc4)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__arm64_sys_add_key
  - security/keys/keyctl.c:__arm64_sys_add_key
```
```
In security/keys/permission.c (ffff800010534178)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffff800010534f7c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffff800010535670)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (ffff800010536894)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffff800010537774)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffff800010537b40)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffff800010537e18)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffff800010538d18)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (ffff80001054bdbc)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (ffff800010571f68)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffff80001146bfcc)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffff8000105acf44)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffff8000105d4998)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffff800010666834)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffff8000109618ec)
Location: include/linux/key.h:138
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
In certs/system_keyring.c (c152c588)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (c04da060)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (c05d9db8)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (c06e6288)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (c06e8cb8)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (c06eb5ac)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/permission.c (c06eb86c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (c06ec67c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (c06ecbe4)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (c06edd6c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (c06ee7dc)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (c06ee93c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (c06eec24)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (c06ef7cc)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (c0702040)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (c0725230)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (c1544c8c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (c075c7c0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (c0782314)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (c080f498)
Location: include/linux/key.h:138
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
In certs/system_keyring.c (c000000001379698)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (c00000000036141c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (c00000000051a0e8)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (c000000000679f80)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (c00000000067e150)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (c000000000681ca8)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/permission.c (c000000000682158)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (c0000000006834a4)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (c000000000683bb8)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (c0000000006852bc)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (c000000000686948)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (c000000000686ba8)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (c000000000686f78)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (c000000000687c80)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (c0000000006a44bc)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (c0000000006d8f58)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (c00000000139ad34)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (c00000000072b50c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (c000000000763018)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (c00000000081c3e4)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (c000000000a174c4)
Location: include/linux/key.h:138
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
In certs/system_keyring.c (ffffffe0000111b8)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffe0001d3b76)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffe0002b65c4)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffe00038f6fc)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffe000391f84)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffe0003940cc)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/permission.c (ffffffe0003943ce)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffe000394fb0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffe0003953d8)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffe0003962b4)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffe000396ba2)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffe000396d52)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffe000396faa)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffe000397982)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (ffffffe0003a65c8)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffe0003c2386)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffe000026f70)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffe0003f5570)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffe000418caa)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffe00049293a)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffe0005cf14e)
Location: include/linux/key.h:138
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
In certs/system_keyring.c (ffffffff828c1e5d)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81218a82)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813447ac)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff8143d393)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8143fc25)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff81442590)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/permission.c (ffffffff81442ae5)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff814437c5)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff81443e93)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff81444ebe)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff81445e02)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81445f85)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff81446280)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff81446d59)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81457314)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81478d9b)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff828dab4c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814ad361)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814d1434)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8155262e)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff8171607e)
Location: include/linux/key.h:138
Inline: True
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
In certs/system_keyring.c (ffffffff828ba585)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff8120bc92)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8133548c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff8142de03)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81430695)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff81432fe0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/permission.c (ffffffff81433535)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff81434215)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff814348e3)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff8143590e)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff81436852)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff814369d5)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff81436cd0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff814377a9)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81447d44)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814697bb)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff828d3268)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8149dd81)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814c1e54)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8154290e)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff816e9afe)
Location: include/linux/key.h:138
Inline: True
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
In certs/system_keyring.c (ffffffff828d4be0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81216822)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8134227c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff81439533)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff8143bdc5)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff8143e730)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/permission.c (ffffffff8143ec85)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff8143f965)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff8143fec2)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:request_key_and_link
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff81440f5e)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff81441ea2)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81442025)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff81442320)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff81442df9)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (ffffffff814533b4)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81474e3b)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff828ed8c0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814a9401)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814cd4c4)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff8154e36e)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81754e4e)
Location: include/linux/key.h:138
Inline: True
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
In certs/system_keyring.c (ffffffff828da001)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff812258a2)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8135557c)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - fs/crypto/keyring.c:search_fscrypt_keyring
```
```
In security/keys/key.c (ffffffff81450723)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/key.c:key_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffff81452f45)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyring.c:find_key_to_update
  - security/keys/keyring.c:keyring_restrict
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:keyring_search_rcu
  - security/keys/keyring.c:search_nested_keyrings
```
```
In security/keys/keyctl.c (ffffffff814558e0)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_move
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/permission.c (ffffffff81455e35)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/permission.c:key_task_permission
```
```
In security/keys/process_keys.c (ffffffff81456b05)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:get_user_session_keyring_rcu
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
```
```
In security/keys/request_key.c (ffffffff814571d3)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_rcu
  - security/keys/request_key.c:construct_key_and_link
```
```
In security/keys/request_key_auth.c (ffffffff81458261)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:key_get_instantiation_authkey
```
```
In security/keys/proc.c (ffffffff814591ed)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81459355)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/keys/dh.c (ffffffff81459650)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/keys/dh.c:dh_data_from_key
```
```
In security/keys/keyctl_pkey.c (ffffffff8145a129)
Location: include/linux/key.h:138
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8146aea4)
Location: include/linux/key.h:138
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8148c7db)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_key_permission
```
```
In security/integrity/digsig.c (ffffffff828f2ce2)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814c1e11)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff814e5f94)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
```
```
In lib/digsig.c (ffffffff815681be)
Location: include/linux/key.h:138
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff817702be)
Location: include/linux/key.h:138
Inline: True
```
</details>
</li>
</ul>

## Differences
