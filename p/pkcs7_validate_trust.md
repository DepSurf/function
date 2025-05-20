# Function: <code>pkcs7_validate_trust</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring, bool *_trusted);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff813ae8c0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:172
Inline: False
Direct callers:
  - certs/system_keyring.c:system_verify_data
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff813ae8c0-ffffffff813aeb45: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff813f25c0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:161
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff813f25c0-ffffffff813f27e8: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff8140be30)
Location: crypto/asymmetric_keys/pkcs7_trust.c:161
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff8140be30-ffffffff8140c058: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff81419a20)
Location: crypto/asymmetric_keys/pkcs7_trust.c:161
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81419a20-ffffffff81419c61: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff81444550)
Location: crypto/asymmetric_keys/pkcs7_trust.c:161
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff81444550-ffffffff81444792: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff814774d0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:162
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814774d0-ffffffff814776f3: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff814956a0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:162
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814956a0-ffffffff814958c3: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff814c3100)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
```
**Symbols:**

```
ffffffff814c3100-ffffffff814c3316: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff814dbf30)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814dbf30-ffffffff814dc146: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff8153b9a0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff8153b9a0-ffffffff8153ba31: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff81558660)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff81558660-ffffffff815586f1: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff81560f90)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
  - certs/blacklist.c:is_key_on_revocation_list
```
**Symbols:**

```
ffffffff81560f90-ffffffff81561021: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff815c23b0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
  - certs/blacklist.c:is_key_on_revocation_list
```
**Symbols:**

```
ffffffff815c23b0-ffffffff815c2441: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff8166c8f0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
  - certs/blacklist.c:is_key_on_revocation_list
```
**Symbols:**

```
ffffffff8166c8f0-ffffffff8166c985: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff81727890)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
  - certs/blacklist.c:is_key_on_revocation_list
```
**Symbols:**

```
ffffffff81727890-ffffffff81727925: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff81763c80)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
  - certs/blacklist.c:is_key_on_revocation_list
```
**Symbols:**

```
ffffffff81763c80-ffffffff81763d15: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff817a58a0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
  - certs/blacklist.c:is_key_on_revocation_list
```
**Symbols:**

```
ffffffff817a58a0-ffffffff817a5935: pkcs7_validate_trust (STB_GLOBAL)
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
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffff8000105d84c0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffff8000105d84c0-ffff8000105d86dc: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (c07859b0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
c07859b0-c0785bac: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (c000000000767b60)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
c000000000767b60-c000000000767e10: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffe00041c0f8)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffe00041c0f8-ffffffe00041c290: pkcs7_validate_trust (STB_GLOBAL)
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
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff814d4510)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814d4510-ffffffff814d4726: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff814c4f30)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814c4f30-ffffffff814c5146: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff814d05a0)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814d05a0-ffffffff814d07b6: pkcs7_validate_trust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pkcs7_validate_trust(struct pkcs7_message *pkcs7, struct key *trust_keyring);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/pkcs7_trust.c (ffffffff814e9070)
Location: crypto/asymmetric_keys/pkcs7_trust.c:158
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_message_sig
```
**Symbols:**

```
ffffffff814e9070-ffffffff814e9280: pkcs7_validate_trust (STB_GLOBAL)
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
<b>Param removed. </b>
<code>bool *_trusted</code>
</li>
</ul>
</details>
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
