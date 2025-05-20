# Function: <code>key_ref_put</code>

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
In certs/system_keyring.c (ffffffff81f86895)
Location: include/linux/key.h:237
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In security/keys/keyctl.c (ffffffff81331ede)
Location: include/linux/key.h:237
Inline: True
Inline callers:
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
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
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffff81334315)
Location: include/linux/key.h:237
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff813360e0)
Location: include/linux/key.h:237
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81336299)
Location: include/linux/key.h:237
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff81f99bc5)
Location: include/linux/key.h:237
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
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
In certs/system_keyring.c (ffffffff81fb0078)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In security/keys/keyctl.c (ffffffff81368480)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_keyring_search
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
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/keys/process_keys.c (ffffffff8136924c)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff8136b0bc)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8136b26c)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff81fc4942)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
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
In certs/system_keyring.c (ffffffff81fec747)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In security/keys/keyctl.c (ffffffff8137ec90)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_keyring_search
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
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/keys/process_keys.c (ffffffff8137fa5c)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff813818cc)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81381a7c)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff82001379)
Location: include/linux/key.h:254
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
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
In certs/system_keyring.c (ffffffff820cd63a)
Location: include/linux/key.h:262
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff811b576a)
Location: include/linux/key.h:262
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/keyctl.c (ffffffff81392bda)
Location: include/linux/key.h:262
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_keyring_search
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
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/keys/process_keys.c (ffffffff8139394a)
Location: include/linux/key.h:262
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff813957fc)
Location: include/linux/key.h:262
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81395970)
Location: include/linux/key.h:262
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff820e4bf4)
Location: include/linux/key.h:262
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
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
In certs/system_keyring.c (ffffffff826d606a)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff811c985a)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff813b4e7c)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff813b8208)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_keyring_search
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
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_add_key
```
```
In security/keys/process_keys.c (ffffffff813b8faa)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff813baf57)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff813bb0f0)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff826ed7fc)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
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
In certs/system_keyring.c (ffffffff8270041f)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff811ea9c3)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff813e5670)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff813e8e07)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_keyring_search
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
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff813e9d44)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff813ebd76)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff813ebed0)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff82717b9c)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_load_x509
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
In certs/system_keyring.c (ffffffff828b756d)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff811fb533)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff813ffe40)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff81403607)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_keyring_search
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
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff81404631)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/proc.c (ffffffff81406981)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81406ad0)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828cf598)
Location: include/linux/key.h:268
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (ffffffff828d0b48)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81212c12)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff8142c52e)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff81430250)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff81431485)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:290
Inline: True
```
```
In security/keys/proc.c (ffffffff81433ab2)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81433c50)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828e90c5)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (ffffffff828d8fc6)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81220432)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff8144627e)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff81449fb0)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff8144b1e5)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:290
Inline: True
```
```
In security/keys/proc.c (ffffffff8144d822)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8144d9c0)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828f1cb2)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (ffffffff82cf867b)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff8124d851)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813929ce)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In security/keys/key.c (ffffffff8149741e)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff8149be58)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff8149cdf2)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff8149f49a)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8149fb4c)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff82d06d09)
Location: include/linux/key.h:310
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (ffffffff82fe5374)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81257c91)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813a3d3e)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In security/keys/key.c (ffffffff814b4ec3)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff814b98f8)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff814ba892)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff814bced8)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff814bd57c)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff82ff412d)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/common.c (ffffffff81bd869d)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - certs/common.c:load_certificate_list
```
```
In certs/blacklist.c (ffffffff8125c1b0)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813aaf7e)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In security/keys/key.c (ffffffff814bad13)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff814bf75b)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff814c070e)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff814c2d76)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff814c33ec)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff831fec01)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/common.c (ffffffff81cb9cf4)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - certs/common.c:load_certificate_list
```
```
In certs/blacklist.c (ffffffff81298060)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff813fa80e)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In security/keys/key.c (ffffffff81513543)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff8151817b)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff8151912e)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff8151b766)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff8151bddc)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff832e5f53)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/blacklist.c (ffffffff812ee603)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8146da75)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
```
```
In security/keys/key.c (ffffffff815a5ba2)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff815aac29)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff815abd73)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff815ad355)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff815ae99b)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff815af039)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff8349cdd1)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff81e8acba)
Location: include/linux/key.h:311
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
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
In certs/blacklist.c (ffffffff81358ab3)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff814fe247)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - fs/crypto/keyring.c:get_keyring_key
```
```
In security/keys/key.c (ffffffff8164f9a2)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff81654fa9)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff816561f3)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff81657a4e)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff8165910b)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81659809)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff83ed4677)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff817262f2)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
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
In certs/blacklist.c (ffffffff8138a423)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff81535829)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - fs/crypto/keyring.c:get_keyring_key
```
```
In security/keys/key.c (ffffffff81688080)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff8168d6c6)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff8168e88e)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816902ce)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff816919a5)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff816920a9)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff836f97b7)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff81762682)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In net/handshake/tlshd.c (ffffffff82094127)
Location: include/linux/key.h:317
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
In certs/system_keyring.c (ffffffff83911f27)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - certs/system_keyring.c:add_to_secondary_keyring
```
```
In certs/blacklist.c (ffffffff813b3f43)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In fs/crypto/keyring.c (ffffffff8156a7f9)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - fs/crypto/keyring.c:get_keyring_key
```
```
In security/keys/key.c (ffffffff816c45a0)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/key.c:__key_create_or_update
  - security/keys/key.c:__key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff816c9c16)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/keyctl.c:__do_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff816cade0)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffff816cc85e)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffff816cdf7f)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff816ce679)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:key_get_persistent
```
```
In security/integrity/digsig.c (ffffffff8392cc25)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
```
In crypto/asymmetric_keys/x509_loader.c (ffffffff817a4142)
Location: include/linux/key.h:317
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_loader.c:x509_load_certificate_list
```
```
In block/sed-opal.c (ffffffff81802654)
Location: include/linux/key.h:317
Inline: True
```
```
In net/handshake/tlshd.c (ffffffff8216aa47)
Location: include/linux/key.h:317
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
In certs/system_keyring.c (ffff800011451bb8)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffff8000102ad6f0)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffff80001052f418)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffff800010533dc4)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__arm64_sys_request_key
  - security/keys/keyctl.c:__arm64_sys_add_key
  - security/keys/keyctl.c:__arm64_sys_add_key
```
```
In security/keys/process_keys.c (ffff800010534f7c)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:290
Inline: True
```
```
In security/keys/proc.c (ffff800010537774)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffff800010537b5c)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffff80001146bfe4)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (c152c5e4)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (c04da060)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (c06e7768)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (c06eb5ac)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/process_keys.c (c06ec67c)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:290
Inline: True
```
```
In security/keys/proc.c (c06ee7dc)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (c06ee958)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (c1544ca4)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (c0000000013796cc)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (c00000000036141c)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (c00000000067c168)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (c000000000681ca8)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/process_keys.c (c0000000006834a4)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:290
Inline: True
```
```
In security/keys/proc.c (c000000000686948)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (c000000000686bc4)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (c00000000139ad50)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (ffffffe0000111e0)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffe0001d3b76)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffe000390bcc)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffe0003940cc)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/keyctl.c:__se_sys_add_key
```
```
In security/keys/process_keys.c (ffffffe000394fb0)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffe000395cf2)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/request_key.c:request_key_and_link
```
```
In security/keys/proc.c (ffffffe000396ba2)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffe000396d68)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffe000026f88)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (ffffffff828c1e77)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81218a82)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff8143e85e)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff81442590)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff814437c5)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:290
Inline: True
```
```
In security/keys/proc.c (ffffffff81445e02)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81445fa0)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828dab66)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (ffffffff828ba59f)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff8120bc92)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff8142f2ce)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff81432fe0)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff81434215)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:290
Inline: True
```
```
In security/keys/proc.c (ffffffff81436852)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff814369f0)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828d3282)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (ffffffff828d4bfa)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff81216822)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff8143a9fe)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff8143e730)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff8143f965)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:290
Inline: True
```
```
In security/keys/proc.c (ffffffff81441ea2)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81442040)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828ed8da)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
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
In certs/system_keyring.c (ffffffff828da01b)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/system_keyring.c:load_system_certificate_list
```
```
In certs/blacklist.c (ffffffff812258a2)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - certs/blacklist.c:is_hash_blacklisted
```
```
In security/keys/key.c (ffffffff81451b3e)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyctl.c (ffffffff814558e0)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
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
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
```
```
In security/keys/process_keys.c (ffffffff81456b05)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (0)
Location: include/linux/key.h:290
Inline: True
```
```
In security/keys/proc.c (ffffffff814591ed)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/proc.c:proc_keys_show
```
```
In security/keys/persistent.c (ffffffff81459370)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
```
```
In security/integrity/digsig.c (ffffffff828f2cfc)
Location: include/linux/key.h:290
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_add_key
```
</details>
</li>
</ul>

## Differences
