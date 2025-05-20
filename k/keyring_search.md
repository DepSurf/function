# Function: <code>keyring_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81331700)
Location: security/keys/keyring.c:889
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/x509_public_key.c:x509_request_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81331700-ffffffff813317c6: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813664a0)
Location: security/keys/keyring.c:913
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff813664a0-ffffffff8136656d: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8137ccc0)
Location: security/keys/keyring.c:913
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8137ccc0-ffffffff8137cd8d: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81390a40)
Location: security/keys/keyring.c:920
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81390a40-ffffffff81390b06: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813b5fe0)
Location: security/keys/keyring.c:917
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff813b5fe0-ffffffff813b60a9: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff813e67e0)
Location: security/keys/keyring.c:910
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff813e67e0-ffffffff813e68a9: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81400fd0)
Location: security/keys/keyring.c:907
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81400fd0-ffffffff814010aa: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8142d800)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8142d800-ffffffff8142d8f0: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81447550)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:search_fscrypt_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81447550-ffffffff81447640: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81498cc0)
Location: security/keys/keyring.c:937
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81498cc0-ffffffff81498db0: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814b6730)
Location: security/keys/keyring.c:937
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814b6730-ffffffff814b6825: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814bc580)
Location: security/keys/keyring.c:937
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814bc580-ffffffff814bc675: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81514fa0)
Location: security/keys/keyring.c:937
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81514fa0-ffffffff81515095: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff815a7720)
Location: security/keys/keyring.c:937
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:find_master_key_user
  - fs/crypto/keyring.c:fscrypt_find_master_key
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff815a7720-ffffffff815a7828: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81651760)
Location: security/keys/keyring.c:937
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:find_master_key_user
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81651760-ffffffff81651868: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8168a010)
Location: security/keys/keyring.c:937
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:find_master_key_user
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8168a010-ffffffff8168a118: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff816c6510)
Location: security/keys/keyring.c:937
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:find_master_key_user
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff816c6510-ffffffff816c6618: keyring_search (STB_GLOBAL)
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffff800010530d50)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:search_fscrypt_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffff800010530d50-ffff800010530e54: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c06e8ba4)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:search_fscrypt_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
c06e8ba4-c06e8ca4: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (c00000000067dfe0)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:search_fscrypt_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
c00000000067dfe0-c00000000067e124: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffe000391e8a)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:search_fscrypt_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffe000391e8a-ffffffe000391f6a: keyring_search (STB_GLOBAL)
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
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143fb30)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:search_fscrypt_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8143fb30-ffffffff8143fc20: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff814305a0)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:search_fscrypt_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff814305a0-ffffffff81430690: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff8143bcd0)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:search_fscrypt_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff8143bcd0-ffffffff8143bdc0: keyring_search (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
key_ref_t keyring_search(key_ref_t keyring, struct key_type *type, const char *description, bool recurse);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyring.c (ffffffff81452e40)
Location: security/keys/keyring.c:941
Inline: False
Direct callers:
  - certs/blacklist.c:is_hash_blacklisted
  - fs/crypto/keyring.c:search_fscrypt_keyring
  - security/keys/keyctl.c:keyctl_keyring_search
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/keys/process_keys.c:look_up_user_keyrings
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key
  - lib/digsig.c:digsig_verify
```
**Symbols:**

```
ffffffff81452e40-ffffffff81452f3a: keyring_search (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool recurse</code>
</li>
</ul>
</details>
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
