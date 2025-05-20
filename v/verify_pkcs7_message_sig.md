# Function: <code>verify_pkcs7_message_sig</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff81220332-ffffffff81220348: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff812201b0-ffffffff812202b1: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff8124d732-ffffffff8124d748: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff8124d5c0-ffffffff8124d6c0: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff81be696c-ffffffff81be6982: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff81257a30-ffffffff81257b30: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:182
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff81bd866d-ffffffff81bd8683: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff8125be90-ffffffff8125bfa2: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:182
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff81cb9cc4-ffffffff81cb9cda: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff81297d40-ffffffff81297e52: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:224
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff81e6b301-ffffffff81e6b317: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff812ee0f0-ffffffff812ee22f: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81358560)
Location: certs/system_keyring.c:224
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff81358560-ffffffff813586b2: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81389df0)
Location: certs/system_keyring.c:232
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff81389df0-ffffffff81389f42: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff813b3920)
Location: certs/system_keyring.c:311
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff813b3920-ffffffff813b3a65: verify_pkcs7_message_sig (STB_GLOBAL)
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
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffff8000102ad3c8)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffff8000102ad3c8-ffff8000102ad4f4: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (c04d9d7c)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
c04d9d7c-c04d9ed4: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (c000000000361000)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
c000000000361000-c0000000003611a8: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffe0001d3882)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffe0001d3882-ffffffe0001d3970: verify_pkcs7_message_sig (STB_GLOBAL)
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
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff81218982-ffffffff81218998: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff81218800-ffffffff81218901: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff8120bb92-ffffffff8120bba8: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff8120ba10-ffffffff8120bb11: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff81216722-ffffffff81216738: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff812165a0-ffffffff812166a1: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_message_sig(const void *data, size_t len, struct pkcs7_message *pkcs7, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:204
Inline: False
Direct callers:
  - certs/system_keyring.c:verify_pkcs7_signature
  - security/integrity/ima/ima_modsig.c:ima_modsig_verify
```
**Symbols:**

```
ffffffff812257a2-ffffffff812257b8: verify_pkcs7_message_sig.cold (STB_LOCAL)
ffffffff81225620-ffffffff81225721: verify_pkcs7_message_sig (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
