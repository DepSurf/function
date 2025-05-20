# Function: <code>keyring_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81330f40)
Location: security/keys/keyring.c:492
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_thread_keyring_to_cred
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81330f40-ffffffff81330fb0: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, int (*restrict_link)(struct key *, const struct key_type *, const union key_payload *), struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81365cd0)
Location: security/keys/keyring.c:492
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_thread_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - security/integrity/ima/ima_mok.c:ima_mok_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81365cd0-ffffffff81365d49: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, int (*restrict_link)(struct key *, const struct key_type *, const union key_payload *), struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8137c4f0)
Location: security/keys/keyring.c:492
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_thread_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8137c4f0-ffffffff8137c569: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813900c0)
Location: security/keys/keyring.c:499
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff813900c0-ffffffff81390131: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813b55f0)
Location: security/keys/keyring.c:494
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff813b55f0-ffffffff813b5661: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813e5e30)
Location: security/keys/keyring.c:494
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff813e5e30-ffffffff813e5e9a: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81400610)
Location: security/keys/keyring.c:494
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/process_keys.c:install_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81400610-ffffffff8140067a: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142cac0)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8142cac0-ffffffff8142cb33: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81446810)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81446810-ffffffff81446883: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81497e00)
Location: security/keys/keyring.c:517
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81497e00-ffffffff81497e73: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b5870)
Location: security/keys/keyring.c:517
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff814b5870-ffffffff814b58e3: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bb6f0)
Location: security/keys/keyring.c:517
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff814bb6f0-ffffffff814bb763: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81513f20)
Location: security/keys/keyring.c:517
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81513f20-ffffffff81513f93: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a64e0)
Location: security/keys/keyring.c:517
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:do_add_master_key
  - fs/crypto/keyring.c:add_new_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff815a64e0-ffffffff815a6578: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81650410)
Location: security/keys/keyring.c:517
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81650410-ffffffff816504a8: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81688cf0)
Location: security/keys/keyring.c:517
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81688cf0-ffffffff81688d88: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c5170)
Location: security/keys/keyring.c:517
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:key_get_persistent
  - security/keys/persistent.c:key_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - security/integrity/digsig.c:integrity_init_keyring
  - block/sed-opal.c:sed_opal_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff816c5170-ffffffff816c5208: keyring_alloc (STB_GLOBAL)
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
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff80001052faf0)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffff80001052faf0-ffff80001052fbc4: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e7dc8)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
c06e7dc8-c06e7e60: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067caa0)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
c00000000067caa0-c00000000067cba4: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe00039122e)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffe00039122e-ffffffe0003912c4: keyring_alloc (STB_GLOBAL)
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
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143edf0)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8143edf0-ffffffff8143ee63: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142f860)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8142f860-ffffffff8142f8d3: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143af90)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8143af90-ffffffff8143b003: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *keyring_alloc(const char *description, kuid_t uid, kgid_t gid, const struct cred *cred, key_perm_t perm, long unsigned int flags, struct key_restriction *restrict_link, struct key *dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814520e0)
Location: security/keys/keyring.c:521
Inline: False
Direct callers:
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/system_keyring.c:system_trusted_keyring_init
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:add_master_key
  - fs/crypto/keyring.c:add_master_key
  - fs/verity/signature.c:fsverity_init_signature
  - security/keys/process_keys.c:join_session_keyring
  - security/keys/process_keys.c:install_session_keyring_to_cred
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/persistent.c:keyctl_get_persistent
  - security/keys/persistent.c:keyctl_get_persistent
  - security/integrity/digsig.c:integrity_init_keyring
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff814520e0-ffffffff81452153: keyring_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int (*restrict_link)(struct key *, const struct key_type *, const union key_payload *)</code>
</li>
<li>
<b>Param reordered. </b>
<code>description, uid, gid, cred, perm, flags, dest</code> ➡️ <code>description, uid, gid, cred, perm, flags, restrict_link, dest</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*restrict_link)(struct key *, const struct key_type *, const union key_payload *)</code> ➡️ <code>struct key_restriction *restrict_link</code>
</li>
</ul>
</details>
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
