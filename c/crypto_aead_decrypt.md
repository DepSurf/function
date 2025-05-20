# Function: <code>crypto_aead_decrypt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff813de83d)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff813f6ddd)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/seqiv.c (ffffffff814031bd)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff813bc098)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8142b89d)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8143911f)
Location: include/crypto/aead.h:355
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff813ecdf4)
Location: include/crypto/aead.h:360
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8145e59d)
Location: include/crypto/aead.h:360
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff8146b3dd)
Location: include/crypto/aead.h:360
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/keys/big_key.c (ffffffff81407f9a)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_crypt
```
```
In crypto/seqiv.c (ffffffff8147be63)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
```
```
In crypto/gcm.c (ffffffff81489718)
Location: include/crypto/aead.h:363
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814a6780)
Location: crypto/aead.c:104
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff814a6780-ffffffff814a67f3: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814c13f0)
Location: crypto/aead.c:105
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff814c13f0-ffffffff814c1463: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81521dc0)
Location: crypto/aead.c:100
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff81521dc0-ffffffff81521e33: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8153ec10)
Location: crypto/aead.c:100
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff8153ec10-ffffffff8153ec83: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff815472b0)
Location: crypto/aead.c:100
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff815472b0-ffffffff81547323: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff815a7a90)
Location: crypto/aead.c:100
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff815a7a90-ffffffff815a7b03: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8164edf0)
Location: crypto/aead.c:100
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff8164edf0-ffffffff8164ee6c: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81708200)
Location: crypto/aead.c:100
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff81708200-ffffffff8170827c: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81741e90)
Location: crypto/aead.c:127
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff81741e90-ffffffff81741ef5: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81782d70)
Location: crypto/aead.c:127
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff81782d70-ffffffff81782dd5: crypto_aead_decrypt (STB_GLOBAL)
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
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffff8000105bb738)
Location: crypto/aead.c:105
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffff8000105bb738-ffff8000105bb7c8: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c0769970)
Location: crypto/aead.c:105
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
c0769970-c07699f4: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c000000000742090)
Location: crypto/aead.c:105
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
c000000000742090-c000000000742168: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffe00040117e)
Location: crypto/aead.c:105
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffe00040117e-ffffffe0004011fa: crypto_aead_decrypt (STB_GLOBAL)
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
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b99d0)
Location: crypto/aead.c:105
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff814b99d0-ffffffff814b9a43: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814aa3f0)
Location: crypto/aead.c:105
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff814aa3f0-ffffffff814aa463: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b5a60)
Location: crypto/aead.c:105
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff814b5a60-ffffffff814b5ad3: crypto_aead_decrypt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_aead_decrypt(struct aead_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814ce500)
Location: crypto/aead.c:105
Inline: False
Direct callers:
  - security/keys/big_key.c:big_key_crypt
  - crypto/seqiv.c:seqiv_aead_decrypt
  - crypto/gcm.c:crypto_rfc4543_crypt
  - crypto/gcm.c:crypto_rfc4106_decrypt
```
**Symbols:**

```
ffffffff814ce500-ffffffff814ce573: crypto_aead_decrypt (STB_GLOBAL)
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
