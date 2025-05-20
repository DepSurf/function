# Function: <code>register_key_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8132fad0)
Location: security/keys/key.c:1071
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8132fad0-ffffffff8132fb71: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff81364820)
Location: security/keys/key.c:1099
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81364820-ffffffff813648c1: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8137b040)
Location: security/keys/key.c:1099
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8137b040-ffffffff8137b0e1: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8138ec10)
Location: security/keys/key.c:1099
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8138ec10-ffffffff8138ecb4: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff813b40d0)
Location: security/keys/key.c:1112
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff813b40d0-ffffffff813b4174: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1112
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff813e56a7-ffffffff813e56db: register_key_type.cold.9 (STB_LOCAL)
ffffffff813e47b0-ffffffff813e482b: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1113
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff813ffe77-ffffffff813ffeb1: register_key_type.cold.9 (STB_LOCAL)
ffffffff813fefa0-ffffffff813ff024: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8142c567-ffffffff8142c5a3: register_key_type.cold (STB_LOCAL)
ffffffff8142b170-ffffffff8142b1f7: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff814462b7-ffffffff814462f3: register_key_type.cold (STB_LOCAL)
ffffffff81444ec0-ffffffff81444f47: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1147
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81497747-ffffffff81497783: register_key_type.cold (STB_LOCAL)
ffffffff81495db0-ffffffff81495e37: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1151
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/trusted-keys/trusted_tpm1.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81befbbc-ffffffff81befbf8: register_key_type.cold (STB_LOCAL)
ffffffff814b3810-ffffffff814b3897: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1151
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81be1c63-ffffffff81be1c9f: register_key_type.cold (STB_LOCAL)
ffffffff814b9640-ffffffff814b96c7: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1151
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81cd2e30-ffffffff81cd2e6c: register_key_type.cold (STB_LOCAL)
ffffffff81511e70-ffffffff81511ef7: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1151
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81e85f98-ffffffff81e85fd3: register_key_type.cold (STB_LOCAL)
ffffffff815a4270-ffffffff815a42fd: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff8164df80)
Location: security/keys/key.c:1151
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8164df80-ffffffff8164e03d: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816867e0)
Location: security/keys/key.c:1214
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff816867e0-ffffffff8168689d: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffff816c2c50)
Location: security/keys/key.c:1210
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_tpm_init
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff816c2c50-ffffffff816c2d0d: register_key_type (STB_GLOBAL)
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
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffff80001052dc90)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffff80001052dc90-ffff80001052dd4c: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c06e6434)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
c06e6434-c06e64e0: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (c00000000067a0c0)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
c00000000067a0c0-c00000000067a394: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/key.c (ffffffe00038f7be)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffe00038f7be-ffffffe00038f876: register_key_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8143e897-ffffffff8143e8d3: register_key_type.cold (STB_LOCAL)
ffffffff8143d4a0-ffffffff8143d527: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8142f307-ffffffff8142f343: register_key_type.cold (STB_LOCAL)
ffffffff8142df10-ffffffff8142df97: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff8143aa37-ffffffff8143aa73: register_key_type.cold (STB_LOCAL)
ffffffff81439640-ffffffff814396c7: register_key_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int register_key_type(struct key_type *ktype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/keys/key.c (0)
Location: security/keys/key.c:1127
Inline: False
Direct callers:
  - certs/blacklist.c:blacklist_init
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - fs/crypto/keyring.c:fscrypt_init_keyring
  - security/keys/big_key.c:big_key_init
  - security/keys/trusted.c:init_trusted
  - security/keys/encrypted-keys/encrypted.c:init_encrypted
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_init
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
**Symbols:**

```
ffffffff81451b77-ffffffff81451bb3: register_key_type.cold (STB_LOCAL)
ffffffff81450830-ffffffff814508b7: register_key_type (STB_GLOBAL)
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
