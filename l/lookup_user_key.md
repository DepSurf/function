# Function: <code>lookup_user_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81333fa0)
Location: security/keys/process_keys.c:516
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/persistent.c:keyctl_get_persistent
```
**Symbols:**

```
ffffffff81333fa0-ffffffff81334476: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81368ea0)
Location: security/keys/process_keys.c:520
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:mpi_from_key
```
**Symbols:**

```
ffffffff81368ea0-ffffffff8136940d: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8137f6b0)
Location: security/keys/process_keys.c:520
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:mpi_from_key
```
**Symbols:**

```
ffffffff8137f6b0-ffffffff8137fc1d: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff813935c0)
Location: security/keys/process_keys.c:531
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff813935c0-ffffffff81393a9d: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff813b8c40)
Location: security/keys/process_keys.c:533
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:SyS_request_key
  - security/keys/keyctl.c:SyS_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff813b8c40-ffffffff813b9123: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff813e99d0)
Location: security/keys/process_keys.c:533
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff813e99d0-ffffffff813e9ebc: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81404400)
Location: security/keys/process_keys.c:533
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_describe_key
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_unlink
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_link
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff81404400-ffffffff814048fc: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81431210)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff81431210-ffffffff814317af: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8144af70)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff8144af70-ffffffff8144b50f: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8149cb60)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
**Symbols:**

```
ffffffff8149cb60-ffffffff8149d1fe: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814ba600)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
**Symbols:**

```
ffffffff814ba600-ffffffff814baca4: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff814c0480)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
**Symbols:**

```
ffffffff814c0480-ffffffff814c0b74: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81518ea0)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
```
**Symbols:**

```
ffffffff81518ea0-ffffffff81519594: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff815abaa0)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - fs/crypto/keyring.c:fscrypt_ioctl_add_key
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
```
**Symbols:**

```
ffffffff815abaa0-ffffffff815ac165: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81655f20)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
  - fs/crypto/keyring.c:get_keyring_key
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
```
**Symbols:**

```
ffffffff81655f20-ffffffff816565e5: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8168e750)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
  - fs/crypto/keyring.c:get_keyring_key
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff8168e750-ffffffff8168ee28: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff816caca0)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
  - fs/crypto/keyring.c:get_keyring_key
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:get_instantiation_keyring
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:__do_sys_request_key
  - security/keys/keyctl.c:__do_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
  - security/keys/keyctl_pkey.c:keyctl_pkey_params_get
  - drivers/nvdimm/security.c:nvdimm_get_user_key_payload
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_accept
```
**Symbols:**

```
ffffffff816caca0-ffffffff816cb37e: lookup_user_key (STB_GLOBAL)
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffff800010534ca8)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__arm64_sys_request_key
  - security/keys/keyctl.c:__arm64_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffff800010534ca8-ffff80001053514c: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (c06ec340)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
c06ec340-c06ec830: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (c000000000683090)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
c000000000683090-c000000000683708: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffe000394d2a)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__se_sys_request_key
  - security/keys/keyctl.c:__se_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffe000394d2a-ffffffe000395130: lookup_user_key (STB_GLOBAL)
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
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81443550)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff81443550-ffffffff81443aef: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81433fa0)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff81433fa0-ffffffff8143453f: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff8143f6f0)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff8143f6f0-ffffffff8143fc8f: lookup_user_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
key_ref_t lookup_user_key(key_serial_t id, long unsigned int lflags, key_perm_t perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/process_keys.c (ffffffff81456890)
Location: security/keys/process_keys.c:611
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_restrict_keyring
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_get_security
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_set_timeout
  - security/keys/keyctl.c:keyctl_setperm_key
  - security/keys/keyctl.c:keyctl_chown_key
  - security/keys/keyctl.c:keyctl_read_key
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
  - security/keys/keyctl.c:keyctl_keyring_clear
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_invalidate_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_revoke_key
  - security/keys/keyctl.c:keyctl_update_key
  - security/keys/keyctl.c:keyctl_get_keyring_ID
  - security/keys/keyctl.c:__ia32_sys_request_key
  - security/keys/keyctl.c:__x64_sys_request_key
  - security/keys/keyctl.c:__ia32_sys_add_key
  - security/keys/keyctl.c:__x64_sys_add_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/dh.c:dh_data_from_key
```
**Symbols:**

```
ffffffff81456890-ffffffff81456e3a: lookup_user_key (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum key_need_perm need_perm</code>
</li>
<li>
<b>Param removed. </b>
<code>key_perm_t perm</code>
</li>
</ul>
</details>
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
