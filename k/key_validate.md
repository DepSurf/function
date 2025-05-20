# Function: <code>key_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff813337d0)
Location: security/keys/permission.c:89
Inline: True
Direct callers:
  - fs/ext4/crypto_key.c:_ext4_get_encryption_info
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/request_key.c:wait_for_key_construction
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813337d0-ffffffff81333816: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81368660)
Location: security/keys/permission.c:89
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:mpi_from_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81368660-ffffffff813686a6: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8137ee70)
Location: security/keys/permission.c:89
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:mpi_from_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8137ee70-ffffffff8137eeb6: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81392dd0)
Location: security/keys/permission.c:89
Inline: True
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81392dd0-ffffffff81392e1a: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff813b8430)
Location: security/keys/permission.c:89
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813b8430-ffffffff813b8476: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff813e91a0)
Location: security/keys/permission.c:89
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813e91a0-ffffffff813e91e6: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81403bd0)
Location: security/keys/permission.c:89
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81403bd0-ffffffff81403c16: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81430840)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81430840-ffffffff81430886: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8144a5a0)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8144a5a0-ffffffff8144a5e6: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8149c150)
Location: security/keys/permission.c:102
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8149c150-ffffffff8149c199: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff814b9bf0)
Location: security/keys/permission.c:102
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814b9bf0-ffffffff814b9c39: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff814bfa70)
Location: security/keys/permission.c:102
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814bfa70-ffffffff814bfab9: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81518490)
Location: security/keys/permission.c:102
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81518490-ffffffff815184d9: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff815aaf90)
Location: security/keys/permission.c:102
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff815aaf90-ffffffff815aafdf: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81655350)
Location: security/keys/permission.c:102
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81655350-ffffffff8165539f: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8168db80)
Location: security/keys/permission.c:102
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8168db80-ffffffff8168dbcf: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff816ca0d0)
Location: security/keys/permission.c:102
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff816ca0d0-ffffffff816ca11f: key_validate (STB_GLOBAL)
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
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffff800010534218)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffff800010534218-ffff80001053427c: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (c06eb910)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c06eb910-c06eb974: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (c000000000682240)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c000000000682240-c0000000006822e8: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffe000394460)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffe000394460-ffffffe0003944b0: key_validate (STB_GLOBAL)
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
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81442b80)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81442b80-ffffffff81442bc6: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff814335d0)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814335d0-ffffffff81433616: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff8143ed20)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8143ed20-ffffffff8143ed66: key_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int key_validate(const struct key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/permission.c (ffffffff81455ed0)
Location: security/keys/permission.c:85
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_find_global_auth_tok_for_sig
  - security/keys/keyctl.c:keyctl_read_key
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:search_process_keyrings_rcu
  - security/keys/request_key.c:wait_for_key_construction
  - security/keys/request_key.c:call_sbin_request_key
  - security/keys/dh.c:dh_data_from_key
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81455ed0-ffffffff81455f16: key_validate (STB_GLOBAL)
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
