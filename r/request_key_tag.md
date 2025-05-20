# Function: <code>request_key_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814325a0)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig.c:integrity_digsig_verify
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814325a0-ffffffff8143262c: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8144c300)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8144c300-ffffffff8144c38c: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8149e3b0)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8149e3b0-ffffffff8149e43c: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814bbea0)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814bbea0-ffffffff814bbf2c: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814c1d70)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814c1d70-ffffffff814c1dfc: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff8151a760)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8151a760-ffffffff8151a7ec: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff815ad530)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff815ad530-ffffffff815ad5ec: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81657ae0)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81657ae0-ffffffff81657b9c: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81690360)
Location: security/keys/request_key.c:706
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81690360-ffffffff8169041c: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff816cc8f0)
Location: security/keys/request_key.c:706
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff816cc8f0-ffffffff816cc9ac: request_key_tag (STB_GLOBAL)
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
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffff800010535fe8)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffff800010535fe8-ffff800010536098: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c06ed678)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/encrypted.c:request_master_key
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c06ed678-c06ed714: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (c0000000006849d0)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c0000000006849d0-c000000000684ab8: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffe000395d00)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffe000395d00-ffffffe000395d80: request_key_tag (STB_GLOBAL)
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
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814448e0)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff814448e0-ffffffff8144496c: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81435330)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81435330-ffffffff814353bc: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81440980)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81440980-ffffffff81440a0c: request_key_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct key *request_key_tag(struct key_type *type, const char *description, struct key_tag *domain_tag, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81457c70)
Location: security/keys/request_key.c:690
Inline: False
Direct callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - drivers/nvdimm/security.c:nvdimm_request_key
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81457c70-ffffffff81457cfc: request_key_tag (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
