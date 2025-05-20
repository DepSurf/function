# Function: <code>verify_pkcs7_signature</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8119f150)
Location: certs/system_keyring.c:208
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff8119f150-ffffffff8119f2c1: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811aec00)
Location: certs/system_keyring.c:208
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff811aec00-ffffffff811aed71: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811b5520)
Location: certs/system_keyring.c:206
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff811b5520-ffffffff811b5666: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff811c9610)
Location: certs/system_keyring.c:206
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff811c9610-ffffffff811c9758: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:207
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff811ea8a7-ffffffff811ea8cf: verify_pkcs7_signature.cold.1 (STB_LOCAL)
ffffffff811ea760-ffffffff811ea888: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:207
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff811fb417-ffffffff811fb43f: verify_pkcs7_signature.cold.0 (STB_LOCAL)
ffffffff811fb2d0-ffffffff811fb3f8: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In certs/system_keyring.c (0)
Location: certs/system_keyring.c:205
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff81212b17-ffffffff81212b2e: verify_pkcs7_signature.cold (STB_LOCAL)
ffffffff812129b0-ffffffff81212afa: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff812202c0)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff812202c0-ffffffff81220332: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8124d6c0)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff8124d6c0-ffffffff8124d732: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81257b30)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff81257b30-ffffffff81257ba2: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8125bfb0)
Location: certs/system_keyring.c:267
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff8125bfb0-ffffffff8125c022: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81297e60)
Location: certs/system_keyring.c:267
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff81297e60-ffffffff81297ed2: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff812ee230)
Location: certs/system_keyring.c:309
Inline: False
Direct callers:
  - kernel/module/signing.c:mod_verify_sig
  - kernel/module/signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff812ee230-ffffffff812ee2b4: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff813586d0)
Location: certs/system_keyring.c:309
Inline: False
Direct callers:
  - kernel/module/signing.c:mod_verify_sig
  - kernel/module/signing.c:mod_verify_sig
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff813586d0-ffffffff81358754: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81389f60)
Location: certs/system_keyring.c:317
Inline: False
Direct callers:
  - kernel/module/signing.c:mod_verify_sig
  - kernel/module/signing.c:mod_verify_sig
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff81389f60-ffffffff81389fe4: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff813b3a80)
Location: certs/system_keyring.c:396
Inline: False
Direct callers:
  - kernel/module/signing.c:mod_verify_sig
  - kernel/module/signing.c:mod_verify_sig
  - kernel/trace/bpf_trace.c:bpf_verify_pkcs7_signature
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff813b3a80-ffffffff813b3b04: verify_pkcs7_signature (STB_GLOBAL)
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
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffff8000102ad4f8)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffff8000102ad4f8-ffff8000102ad59c: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (c04d9ed4)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
c04d9ed4-c04d9f54: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (c0000000003611b0)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
c0000000003611b0-c0000000003612c4: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffe0001d3970)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffe0001d3970-ffffffe0001d39fa: verify_pkcs7_signature (STB_GLOBAL)
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
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81218910)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff81218910-ffffffff81218982: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff8120bb20)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff8120bb20-ffffffff8120bb92: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff812166b0)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff812166b0-ffffffff81216722: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int verify_pkcs7_signature(const void *data, size_t len, const void *raw_pkcs7, size_t pkcs7_len, struct key *trusted_keys, enum key_being_used_for usage, int (*view_content)(void *, const void *, size_t, size_t), void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In certs/system_keyring.c (ffffffff81225730)
Location: certs/system_keyring.c:283
Inline: False
Direct callers:
  - kernel/module_signing.c:mod_verify_sig
  - kernel/module_signing.c:mod_verify_sig
  - fs/verity/signature.c:fsverity_verify_signature
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
**Symbols:**

```
ffffffff81225730-ffffffff812257a2: verify_pkcs7_signature (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
