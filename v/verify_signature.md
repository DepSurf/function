# Function: <code>verify_signature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff813ac580)
Location: crypto/asymmetric_keys/signature.c:28
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff813ac580-ffffffff813ac5c5: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff813f04a0)
Location: crypto/asymmetric_keys/signature.c:46
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff813f04a0-ffffffff813f04e5: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81409d20)
Location: crypto/asymmetric_keys/signature.c:46
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff81409d20-ffffffff81409d65: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81417850)
Location: crypto/asymmetric_keys/signature.c:46
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff81417850-ffffffff81417896: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814422b0)
Location: crypto/asymmetric_keys/signature.c:46
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814422b0-ffffffff814422f9: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81475190)
Location: crypto/asymmetric_keys/signature.c:46
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff81475190-ffffffff814751d8: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81492e20)
Location: crypto/asymmetric_keys/signature.c:141
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff81492e20-ffffffff81492e68: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814c0520)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814c0520-ffffffff814c0568: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814d9370)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814d9370-ffffffff814d93b8: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81538c40)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff81538c40-ffffffff81538c88: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81555a40)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff81555a40-ffffffff81555a88: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff8155e1b0)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff8155e1b0-ffffffff8155e1f8: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff815bf4e0)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff815bf4e0-ffffffff815bf528: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81669380)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff81669380-ffffffff816693e0: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff81723c20)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff81723c20-ffffffff81723c80: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff8175ffa0)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff8175ffa0-ffffffff81760000: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff817a18d0)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
```
**Symbols:**

```
ffffffff817a18d0-ffffffff817a1930: verify_signature (STB_GLOBAL)
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
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffff8000105d5478)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffff8000105d5478-ffff8000105d54e8: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (c0782d5c)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
c0782d5c-c0782dc4: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (c000000000763850)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
c000000000763850-c0000000007638e0: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffe0004196b4)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffe0004196b4-ffffffe000419704: verify_signature (STB_GLOBAL)
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
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814d1950)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814d1950-ffffffff814d1998: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814c2370)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814c2370-ffffffff814c23b8: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814cd9e0)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814cd9e0-ffffffff814cda28: verify_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int verify_signature(const struct key *key, const struct public_key_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/signature.c (ffffffff814e64b0)
Location: crypto/asymmetric_keys/signature.c:137
Inline: False
Direct callers:
  - security/integrity/digsig_asymmetric.c:asymmetric_verify
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_verify_signature
  - crypto/asymmetric_keys/restrict.c:key_or_keyring_common
  - crypto/asymmetric_keys/restrict.c:restrict_link_by_signature
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
  - crypto/asymmetric_keys/pkcs7_trust.c:pkcs7_validate_trust
```
**Symbols:**

```
ffffffff814e64b0-ffffffff814e64f8: verify_signature (STB_GLOBAL)
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
