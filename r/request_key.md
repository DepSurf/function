# Function: <code>request_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct key *request_key(struct key_type *type, const char *description, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81335040)
Location: security/keys/request_key.c:619
Inline: False
Direct callers:
  - fs/ext4/crypto_key.c:_ext4_get_encryption_info
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig.c:integrity_digsig_verify
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81335040-ffffffff813350e0: request_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct key *request_key(struct key_type *type, const char *description, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81369fc0)
Location: security/keys/request_key.c:619
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig.c:integrity_digsig_verify
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81369fc0-ffffffff8136a04f: request_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct key *request_key(struct key_type *type, const char *description, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813807d0)
Location: security/keys/request_key.c:619
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig.c:integrity_digsig_verify
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813807d0-ffffffff8138085f: request_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct key *request_key(struct key_type *type, const char *description, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff81394640)
Location: security/keys/request_key.c:620
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig.c:integrity_digsig_verify
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81394640-ffffffff813946cb: request_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct key *request_key(struct key_type *type, const char *description, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813b9da0)
Location: security/keys/request_key.c:645
Inline: False
Direct callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
  - security/integrity/digsig.c:integrity_digsig_verify
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - security/integrity/evm/evm_crypto.c:evm_init_key
  - lib/digsig.c:digsig_verify
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813b9da0-ffffffff813b9e2b: request_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct key *request_key(struct key_type *type, const char *description, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff813eaad0)
Location: security/keys/request_key.c:645
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
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff813eaad0-ffffffff813eab4f: request_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct key *request_key(struct key_type *type, const char *description, const char *callout_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/request_key.c (ffffffff814054f0)
Location: security/keys/request_key.c:632
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
ffffffff814054f0-ffffffff8140556f: request_key (STB_GLOBAL)
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
In fs/crypto/keyinfo.c (ffffffff813380fb)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff813fef45)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81437c87)
Location: include/linux/key.h:319
Inline: True
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff81439185)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff8149aa1c)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_digsig_verify
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8149abf2)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a28a5)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff815392e8)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff8173d9e2)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff8134e1ab)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff81418e35)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814519b7)
Location: include/linux/key.h:319
Inline: True
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff81452ff5)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff814b4b9f)
Location: include/linux/key.h:319
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814b4e42)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814bd575)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff8155a108)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81761862)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff8139408b)
Location: include/linux/key.h:339
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff81468005)
Location: include/linux/key.h:339
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814a3f48)
Location: include/linux/key.h:339
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:request_master_key
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff814a5885)
Location: include/linux/key.h:339
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff815140ef)
Location: include/linux/key.h:339
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff815142c5)
Location: include/linux/key.h:339
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8151de45)
Location: include/linux/key.h:339
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff815e3a3d)
Location: include/linux/key.h:339
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff818214f2)
Location: include/linux/key.h:339
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff813a554b)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff81483490)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c1768)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:request_master_key
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff814c2df5)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff8153126f)
Location: include/linux/key.h:340
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8153142d)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8153acc5)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff81607ecd)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81830202)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff813ac62b)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff81488f20)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814c7c38)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:request_master_key
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff814c9265)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff8153969f)
Location: include/linux/key.h:340
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8153985d)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815433a5)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff815eabdd)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81813492)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff813fbf9b)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff814e0720)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81520728)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:request_master_key
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff81521d55)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff81597f11)
Location: include/linux/key.h:340
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff815981a7)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815a3ad5)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff816570dd)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff8189dad2)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff8146f39c)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff8156e8b0)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff815b3e54)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:request_master_key
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff815b57a5)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff8163c72d)
Location: include/linux/key.h:340
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8163ca35)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8164a3e5)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff8176e928)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff819e7530)
Location: include/linux/key.h:340
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff81500adc)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff81613320)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8165eb84)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:request_master_key
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff81660835)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff816f3f9d)
Location: include/linux/key.h:346
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff816f4303)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In security/integrity/evm/evm_crypto.c (ffffffff817034f5)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff8189e218)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81b63760)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff8153816c)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff8164b370)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816974d4)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:request_master_key
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff81699175)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff8172e0d0)
Location: include/linux/key.h:346
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8172e405)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8173d525)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff818e07d8)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81bb6d60)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff8156d2bc)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff81684840)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d3b54)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:request_master_key
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff816d5825)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff8176ea30)
Location: include/linux/key.h:346
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8176ed65)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:request_asymmetric_key
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8177e355)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff81927318)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81c0b3b0)
Location: include/linux/key.h:346
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffff80001040f454)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa64c)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053ca18)
Location: include/linux/key.h:319
Inline: True
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffff80001053dee4)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffff8000105acd2c)
Location: include/linux/key.h:319
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffff8000105ad00c)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (ffff8000105b6494)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffff800010666904)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffff800010961788)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (c05dbf10)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (c06b7dc4)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (c06f27a4)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:request_master_key
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (c06f3e90)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (c075c5dc)
Location: include/linux/key.h:319
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (c075c894)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (c07654b8)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (c080f564)
Location: include/linux/key.h:319
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
In fs/crypto/keysetup_v1.c (c00000000051cc40)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (c00000000063cdfc)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068c4c0)
Location: include/linux/key.h:319
Inline: True
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (c00000000068e178)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (c00000000072b214)
Location: include/linux/key.h:319
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (c00000000072b608)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (c00000000073a4c0)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (c00000000081c4f0)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (c000000000a172f4)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffe0002b805c)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffe000368e84)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a63c)
Location: include/linux/key.h:319
Inline: True
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffe00039b75c)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffe0003f535a)
Location: include/linux/key.h:319
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffe0003f5634)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffe0003fd120)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffe0004929e6)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffe0005cf00e)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff8134678b)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff81411415)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81449f97)
Location: include/linux/key.h:319
Inline: True
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff8144b5d5)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff814ad17f)
Location: include/linux/key.h:319
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814ad422)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b5b55)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff815526e8)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81715f52)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff8133746b)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff81401e95)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143a9e7)
Location: include/linux/key.h:319
Inline: True
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff8143c025)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff8149db9f)
Location: include/linux/key.h:319
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff8149de42)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a6575)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff815429c8)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff816e99d2)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff8134425b)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff8140e795)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446037)
Location: include/linux/key.h:319
Inline: True
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff81447675)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff814a921f)
Location: include/linux/key.h:319
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814a94c2)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b1be5)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff8154e428)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81754d22)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
In fs/crypto/keysetup_v1.c (ffffffff8135753b)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_and_lock_process_key
```
```
In fs/ecryptfs/keystore.c (ffffffff81424405)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
  - fs/ecryptfs/keystore.c:ecryptfs_keyring_auth_tok_for_sig
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d367)
Location: include/linux/key.h:319
Inline: True
```
```
In security/keys/encrypted-keys/masterkey_trusted.c (ffffffff8145e9a5)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/keys/encrypted-keys/masterkey_trusted.c:request_trusted_key
```
```
In security/integrity/digsig.c (ffffffff814c1c2f)
Location: include/linux/key.h:319
Inline: True
```
```
In security/integrity/digsig_asymmetric.c (ffffffff814c1ed2)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814ca665)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
```
In lib/digsig.c (ffffffff81568278)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/nvdimm/security.c (ffffffff81770192)
Location: include/linux/key.h:319
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_request_key
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
</ul>
